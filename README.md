## Data
#### Directory Structure

```
data
    data_main     # For diagonal-line hatching
        train_data        # training set    
        val_data          # validation set
        test_data         # testing set
        demo_real_data    # real dirty data used for hatching removal demo

    data_combination   # For combined hatching
        train_data        # training set    
        val_data          # validation set
        test_data         # testing set
        demo_real_data    # real dirty data used for hatching removal demo

    helck     # Real dirty data handwritten by Helck. Used for hatching removal demo

    shade     # standalone diagonal-line hatching blocks
        shade_train   # used for synthesizing training set
        shade_val   # used for synthesizing validation set
        shade_test   # used for synthesizing testing set

    bracket     # standalone bracket hatching blocks
        bracket_train   # used for synthesizing training set
        bracket_val   # used for synthesizing validation set
        bracket_test   # used for synthesizing testing set

```

## forOcrDemo
Here are a few pictures that have been resized to fit the size processed by PhilologEg, along with the OCR results.

