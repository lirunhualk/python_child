# python_child

面向小学生的 Python 学习课件仓库。

这个仓库适合存放课堂用的 Jupyter Notebook。推荐做法是：一个主题课件对应一个 `.ipynb`，在 notebook 内按“第 1 课、第 2 课……”拆成多节课，方便老师按课时推进，也方便学生课后继续打开练习。

## 目录

- `notebooks/`：正式课件 notebook。
- `assets/`：图片、音频、数据文件等课件素材。
- `docs/`：课件编写规范和维护说明。

## 当前课件

- `notebooks/01_python_first_steps.ipynb`：Python 入门：让电脑听我说。包含输出、变量、条件判断、循环和一个口算出题机小项目。

## 使用方式

1. 用 VS Code、JupyterLab 或 Jupyter Notebook 打开 `notebooks/` 下的 `.ipynb` 文件。
2. 从上到下运行代码单元格。
3. 让学生优先修改“试一试”“小挑战”中的代码，再观察输出变化。

## 编写约定

- 每个 notebook 聚焦一个主题，不把太多无关内容塞进同一个文件。
- 每节课固定包含：目标、演示、学生练习、挑战、回顾。
- 代码示例尽量短，变量名清楚，少用复杂依赖。
- 面向小学生时优先使用生活化主题，例如姓名、分数、小游戏、口算、图形、故事。
- 详细规范见 `docs/courseware-guidelines.md`。
