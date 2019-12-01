
### To check which rows are null in a dataframe

nan_rows = df[df.isnull().T.any().T]
