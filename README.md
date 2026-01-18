這可以模擬16-QAM與64-QAM的情況，
若要模擬16-QAM，則變數code_list需要長度16的list並註解掉長度64的list，
而function get_mean_BER()註解掉的部分是模擬64-QAM用的，模擬16-QAM並不需要變動該function。
