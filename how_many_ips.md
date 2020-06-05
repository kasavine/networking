# Question 5

What is the maximum number of ip addresses that can be assigned to host on a local subnet that uses theXXXXXXXXXX subnet mask?

    255.0.0.0: 1111 1111. 0000 0000. 0000 0000. 0000 0000 - 2^24 = 16, 777, 216 - 2 = 16, 777, 214
                            256 * 256 * 256 = 16, 777, 216 - 2 = 16, 777, 214

    255.192.0.0: 1111 1111. 1100 0000. 0000 0000. 0000 0000 - 2^22 = 4, 194, 304 - 2 = 4, 194, 302
                         (256 - 192) * 256 * 256 = 4, 194, 304 - 2  = 4, 194, 302

    255.240.0.0: 1111 1111. 1111 0000. 0000 0000. 0000 0000 - 2^20 = 1, 048, 576 - 2 = 1, 048, 574
                          (256 - 240) * 256 * 256 = 1, 048, 576 - 2 = 1, 048, 574

    255.254.0.0: 1111 1111. 1111 1110. 0000 0000. 0000 0000 - 2^17 = 131, 072 - 2 = 131, 070
                          (256 - 254) * 256 * 256 = 131, 072 - 2

    255.255.192.0: 1111 1111. 1111 1111. 1100 0000. 0000 0000 - 2^14 = 16, 384 - 2 = 16, 382
                                        (256 - 192) * 256 = 16, 384 - 2 = 16, 382

    255.255.255.224: 1111 1111. 1111 1111. 1111 1111. 1110 0000 - 2^5 = 32 - 2 = 30
                                                    (256 - 224) = 32 - 2 = 30

    255.255.255.248: 1111 1111. 1111 1111. 1111 1111. 1111 1000 - 2^3 = 8 - 2 = 6
                                                    (256 - 248) = 8 - 2 = 6