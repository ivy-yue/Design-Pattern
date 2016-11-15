# Design-Pattern
Task 2
這次課程中有 Composite, Observer, Undo/Redo 三個題 給的是 Java examples, 我在今天最後 堂課中告訴學 們，如果把這三個 design patterns 改以 C++ 實作，也很棒。 這三個題 中，Undo/Redo 層次最 規模最 ，Composite 次之，Observer  次之。 如果學 選擇這三個題 ，盼您能接受，並且按上述難 程度酌 給予加權.

#Learning Process
Composite 27
將物件(s) 組成/構成 為樹狀結構，用以表示 "局部-全部" 階層體系。 Composite 可以讓 clients 以一致的方式對待「個別物件」和「合成物件」。
常見例子:
•File system:directory 內有許多 files。然而 files 和 directories 被一視同仁。 
•Windowing system:每一個視窗內還可以再開視窗。 
•另，本身是樹狀結構的 data structures，也就相當於 Composite。 
•Command 中建立 macro command 時也會用到 Composite。


Undo/Redo 124
將 request 封裝為 object，讓你得藉由不同的 requests 來參數化 clients ，或將 requests 放 進 queue 中或作為 log 保存下來，且能支援 undoable 操作。

Observer 14
在 objects 之間定義 "一對多" 依存性，使得當 object 改變狀態時，它所 依存的所有 objects 都會獲得通知並自動更新。
Observer 是被動地被通知，而不是主動觀察，所以這個 pattern 的另一 個名稱 publish-subscribe 也許更合適些。
