# 2026.03.23 – 2026.03.29

## PRs
1. rems-project/sail（进行中） – Lean：修复了浮点库中 fp_bits 编译被跳过的问题。我尝试添加了一些修改，但目前被阻塞，因为 Lean 4 依赖于 rems-project/lean-sail。
2. rems-project/lean-sail（进行中） – 这是 sail 项目的一个子部分。我们需要先将其合并到rems-projects/lean-sail中，第一部分才能正常工作。为 Sigma 类型添加了 Inhabited 和 BEq 实例。