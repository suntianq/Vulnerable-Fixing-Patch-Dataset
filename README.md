# Vulnerable-Fixing-Patch-Dataset

#### Data Description

| Name in the Json | Description                                                  |
| ---------------- | ------------------------------------------------------------ |
| CVE              | Common Weakness Enumeration ID                               |
| CWE              | Common Vulnerabilities and Exposures ID                      |
| label            | Whether the patch is a vulnerability fix patch, if yes then it is 1, if not then it is 0 |
| commit           | Commit ID in code repository                                 |
| owner            | Software owner                                               |
| repo             | Software name                                                |
| source           | Source of this commit                                        |
| language         | The programming language of the commit                       |
| date             | The date the patch was submitted                             |
| msg_tokens_len   | The token length of the patch commit message                 |
| msg_line_len     | The number of lines in the patch commit message              |
| change_count     | Statistics of patch code changes, including the number of files modified, lines added, and lines deleted. |

​	
