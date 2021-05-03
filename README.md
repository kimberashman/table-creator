# table-creator
Convert csv table into a LaTeX formatted table

#### Example output:
![Example](/Example.png)

#### Example LaTeX:
\begin{table}[htbp]
\caption{Insert Caption}\label{tab1}
\resizebox{\columnwidth}{!}{\begin{tabular}{|p{0.17\linewidth}|p{0.17\linewidth}|p{0.17\linewidth}|p{0.17\linewidth}|p{0.17\linewidth}|p{0.17\linewidth}|}
\hline
ID&Task 1 &Task 2&Task 3&Task 4&End \\
\hline
1AA & 48071 & 48175.0 & 48205 & 48301 & 48405 \\
\hline
1AB & 48729 & NaN & 48776 & 48818 & 48878 \\
\hline
1AC & 48936 & NaN & 49001 & 49056 & 49103 \\
\hline
1AD & 49177 & NaN & 49216 & 49265 & 49290 \\
\hline
1AE & 49354 & NaN & 49389 & 49495 & 49498 \\
\hline
1AF & 49569 & NaN & 49592 & 49592 & 49621 \\
\hline
1AG & 49685 & NaN & 49704 & 49704 & 49740 \\
\hline
1-E1 & 49806 & NaN & 49834 & 49893 & 49922 \\
\hline
1-F1 & 49992 & NaN & 50017 & 50017 & 50115 \\
\hline
1-G1 & 50181 & NaN & 50208 & 50208 & 50290 \\
\hline
1-H1 & 50363 & NaN & 50372 & 50372 & 50425 \\
\hline
1-I1 & 50497 & NaN & 50514 & 50514 & 50553 \\
\hline
1-J1 & 50602 & NaN & 50614 & 50783 & 50824 \\
\hline
1-K1 & 51044 & NaN & 51078 & 51234 & 51242 \\
\hline
1-L1 & 51414 & NaN & 51425 & 51425 & 51444 \\
\hline
1-M1 & 51512 & NaN & 51525 & 51525 & 51550 \\
\hline
1-N1 & 51581 & NaN & 51608 & 51608 & 51629 \\
\hline
1-O1 & 51713 & NaN & 51769 & 51769 & 51822 \\
\hline
1-P1 & 51903 & NaN & 51939 & 52020 & 52087 \\
\hline
1-Q1 & 52189 & NaN & 52244 & 52358 & 52409 \\
\hline
1-R1 & 52462 & 52485.0 & 52530 & 52596 & 52642 \\
\hline
1-S1 & 52695 & 52720.0 & 52737 & 52792 & 52815 \\
\hline
1-T1 & 52817 & 52904.0 & 52925 & 53021 & 53038 \\
\hline
1-U1 & 53097 & 53111.0 & 53105 & 53202 & 53245 \\
\hline
1-V1 & 53313 & 53327.0 & 53339 & 53339 & 53377 \\
\hline
\end{tabular}}
\end{table}
