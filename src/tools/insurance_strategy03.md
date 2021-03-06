# 期权策略篇之“保险策略（三）”

保险策略是个人投资者使用非常广泛的策略，在实际应用中，投资者可能会遇到一些问题。

1. 保险策略对什么样的投资者具有吸引力？

    这一策略可能对两类投资者而言更为需要。第一类投资者是不想卖出股票的长期持有者，他们可以运用认沽期权的保护来限制短期内可能下跌而导致的亏损。第二类投资者是在买入股票时举棋不定、生怕自己错买的投资者，他们往往希望有某种“保险”，以防看错个股的走向。

2. 简单地直接买入股票与保险策略孰优孰劣？

    这个问题没有肯定的答案，这就好比我们是否要为自己的财产买一份保险一样，更多地取决于投资者自身的风险偏好程度和对市场判断的自信程度。如果投资者对自己买入的股票十分有信心，风险偏好程度较高，那么他完全可以不买认沽期权作保护；而对于风险承受能力较差的投资者，他们在买入股票或持有股票的同时，往往担心后市的下跌风险，此时采用保险策略将是一个不错的选择。

3. 保险策略具有止损的功能，那么与“止损订单”有何区别呢？

    止损订单是被动的止损方式，是价格依赖的。它的优点在于没有止损成本，但缺点在于：若股价跳空止损价位后一直下跌，则投资者将无法及时止损，或者若股价触及止损价位后开始回升，则投资者将不得不以止损价位割抛手中的股票，反而失去回升反弹的收益。

    保险策略是一种主动的止损方式，是时间依赖的。它的优点在于投资者通过预先支付权利金，锁定股票在到期日的卖出价位，从而在到期日前可“高枕无忧”；但缺点在于其止损功能具有时间限制，随着合约到期而失效，同时它是一种有成本的止损方式。

4. 从损益图看，保险策略和买入认购期权类似，这两个策略是不是一回事呢？

    答案是否定的。损益图的相似只是告诉我们这两个策略的潜在盈亏是相似的。但从头寸的角度来说，这两个策略具有本质的不同。

    认购期权的建仓成本只有权利金，而保险策略的建仓成本等于股票的购买价格加上认沽期权的权利金，相比之下，后者高出很多。

    保险策略的建仓者实际持有股票，因此享有股票分红派息收益权，而认购期权的建仓者在到期前未持有股票，所以认购期权的持有者无法得到股票分红收益。

5. 市场上有这么多认沽期权合约，应该选择哪一个合约对股票作保护呢？

    （1）到期日的选择

    首先，这就像买保险的保险期，取决于投资者想要保护手中股票的时间段。

    其次，通常而言，长期保险的保费一定会比短期保险的保费贵，因此远月的一般比近月的贵。

    在实际操作过程中，比较常见的做法是：先买入近月的认沽期权，待合约到期时，再行判断是否要买入下一个月的认沽期权。这一操作的优点在于降低了保险的成本，灵活地根据标的股票的价格走势而作判断。

    （2）行权价的选择

    首先，深度虚值的认沽期权虽然成本很低，但它所提供的下跌保护范围很小。它更像是一份“灾难保险”，当股价仅为小幅下跌时，它提供不了保护。

    其次，深度实值的认沽期权虽然保护的范围很大，但它的权利金太高，严重限制了投资者的潜在盈利。这是一种过度保守的策略，其较高的权利金支出很大程度上抵消了股价的上涨收益。

    因此，在实际操作中，投资者通常可以买入轻度虚值、平值或轻度实值的认沽期权。这样，投资者可以在保护股票下跌风险和保留股票上涨收益之间达到一种平衡。

小结

保险策略是一种风险有限、潜在收益无限的保守型套保策略，适合于希望持有股票，但风险承受能力较弱的投资者。一方面防范了后市的下跌风险，另一方面又保留了股价的上涨收益。投资者在实际投资过程中，可根据自身对股价的判断和风险偏好，选择是否买入认沽期权作保护性对冲，以及如何合适地选择期权合约的行权价和到期日，逐步学会巧用认沽期权穿越牛熊市。
