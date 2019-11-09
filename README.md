# hising-dataset

Files are saved using pickle library. Unpickled object is a list of two dictionaries. First dictionary contains (linear terms index, coefficient) as (key, value) pair. Second dictionary contains (higher order term, coefficient) as (key, value) pair. Every higher order term is a tuple of indexes corresponding to the variables present in the term.
