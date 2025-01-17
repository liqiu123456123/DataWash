# DataWash

DataWash 是一个用于数据清洗的 Python 库。它提供了各种模块和函数，用于处理缺失值、检测和处理异常值、转换数据格式、处理重复数据、转换数据类型以及特征标准化和归一化。

## 安装

你可以使用 pip 安装该库：

```sh
pip install DataWash


模块和函数
缺失值处理
fill_missing_values(df, method='mean', column=None)
drop_missing_values(df, axis=0)
mark_missing_values(df, column=None, marker='missing')
异常值检测与处理
detect_outliers(df, method='zscore', column=None)
handle_outliers(df, method='drop')
数据格式转换
convert_time_format(df, column, format='%Y-%m-%d')
encode_categorical(df, column, method='onehot')
重复数据处理
identify_duplicates(df)
drop_duplicates(df)
merge_duplicates(df, by, method='mean')
数据类型转换
auto_convert_types(df)
特征标准化与归一化
standardize_features(df, columns)
normalize_features(df, columns, range_min=0, range_max=1)