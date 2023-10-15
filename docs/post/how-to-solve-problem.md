# 如何解决问题

## 流程：

  ```mermaid
  graph TB
  A(遇到问题) --> B{是否有现成的答案?}
  B --> |有| Q[解决问题]
  B --> |没有| C{尝试自己解决}
  C --> |无法解决| D[请教有关人员] --> Q
  C --> |解决了| Q
  Q --> E{有记录的价值吗?}
  E --> |有| F[记录并发布供他人参考]
  F --> |提供来源| B
  ```

  在本次项目中，我就把使用 FastFFI 所遇到的问题和对应的解决办法记录了下来，并准备以此为 FastFF 贡献一个 PR：![image-20230924154512861](C:\Users\John Dylan\AppData\Roaming\Typora\typora-user-images\image-20230924154512861.png)

## 思路

要解决问题，首先需要明确问题的需求，再拆分为更小的步骤，最后逐一解决。

## 途径：

ChatGPT—搜索引擎—官方文档—询问专家。可靠性递增，方便性递减。VPN：Google, NewBing 和 GitHub;

如果需要询问他人，则必须理清问题，明确自己的需求，说出做过的尝试，这样解决问题的效率会更高。![image-20230924152148378](C:\Users\John Dylan\AppData\Roaming\Typora\typora-user-images\image-20230924152148378.png)

