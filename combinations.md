
| RISC-V |    | Quark                        |             |
|--------|----|------------------------------|-------------|
| LUI    | 32 | LIT{4,8,16,32} JMP           | 16,20,28,44 |
| AUIPC  | 32 | LIT{4,8,16,32}               | 8,12,20,36  |
| ADDI   | 32 | LIT{4,8,16,32} add           | 16,20,28,44 |
| ADD    | 32 | add                          | 8           |
| LW     | 32 | LIT{4,8,16,32} add load16_u  | 24,28,36,52 |
| SW     | 32 | LIT{4,8,16,32} add store16_u | 24,28,36,52 |