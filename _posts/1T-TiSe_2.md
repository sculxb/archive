#  $1T-TiSe_2$

### Unconventional Charge-Density-Wave Transition in Monolayer $1T‑TiSe_2$

作者分别做了室温和40K下的单层$TiSe_2$的ARPES测量。

单层$TiSe_2$长在$SiC$(0001)面上的双层石墨烯上。先做了高能电子衍射谱(RHEED)证明1x1的$TiSe_2$结构。从STM可以看到1x1的结构和2x2的结构。

![选区_293](/home/cris/图片/截图/选区_293.png)

上面是分别做的室温下和40K低温下ARPES测量。下面的是根据能量分布作的统计。可以看出，室温下在$\Gamma$点上有两条holelike的带。根据下面的统计可以看出来在M点上有一个electron pocket。但是没有看到hole pocket，作者认为这是由于$Se$空位导致的电子掺杂或者是衬底上的电荷转移导致的。能带计算中$1T-TiSe2_2$有一个-0.2eV的间接带隙，但是在实验中带隙几乎为0。从右图中可以看到，在$T=40K$下，两个holelike带出现了。

费米面附近

![选区_294](/home/cris/图片/截图/选区_294.png)

图中a和c是室温下的测量，b和d是40K的数据，在$\Gamma$点上，低温下两条带都向下移动了0.08eV

e图是对比40K下Se1，Se2的intensity和X1，X2的intensity，可以看出两者能量峰位完全相同。非常明白的指出了X1，X2是Se1，Se2的复制。同时图b中在$\Gamma$点上面也有M点的electron pocket 的复制(比较模糊)，这个指出单层$1T-TiSe_2​$在低温下也出现了CDW相变。

他们做了变温实验。

![选区_296](/home/cris/图片/截图/选区_296.png)

可以看到在180K以下，Se1,Se2的峰位出现了shift，X1,X2则是在200K以上消失了，由此作者认为$1T-TiSe_2​$在200K附近也有一个CDW相变，与体相相同。但是比之前报道的薄层(<100nm)中的240K相比减小了40K。作者认为这可能是由于电子doping引起的。

除此之外，作者还测到CDW相的能隙为180meV，比体相的110meV大，所以认为单层中电子-空穴耦合更强。

------

### Influence of Domain Walls in the Incommensurate Charge Density Wave State of Cu Intercalated $1T-TiSe_2$

by Shichao Yan *et. al.*  PRL 118, 106405 (2017)

文章分别做了$1T-TiSe_2​$和$Cu_{0.08}TiSe_2​$的低温STM(6K)，在原始的$1T-TiSe_2​$中，作者发现长程均匀的相称CDW（CCDW）相。在$Cu_{0.08}TiSe_2​$中发现非相称CDW（ICDW）相（In contrast, $Cu_{0.08}TiSe_2​$ displays an incommensurate CDW (ICDW) phase with localized CCDW domains separated by domain walls).又做了不同偏压下的STS谱，发现在费米面附近有额外的费米子，并认为它们对超导的出现起到很重要的作用。认为电声耦合是ICDW相中形成的CDW相的主要原因。

$1T-TiSe_2$在体相的CDW相变温度为202K，单层中相变温度为240K，同时在对体相进行铜原子插层的时候，随着掺杂浓度的提高，CDW相变温度不断降低，超导相从$x\sim 0.04$开始出现，在$x\sim 0.08$的掺杂浓度上打到最大超导转变温度4.2K。通过STS实验，得到能隙大概为120meV，与之前的ARPES实验结果相同。他们想了一种可以更好的分辨CDW相的方法，先对STM图作傅里叶变换，得到衍射半点，然后对CDW的斑点做逆傅里叶变换，发现在原始的$1T-TiSe_2$中没有畴壁的存在。图c中黄圈圈的就是CDW在傅里叶变换图中的斑点。

![选区_320](/home/cris/图片/截图/选区_320.png)

然后开始做$Cu_{0.08}TiSe_2$的实验，可以看到CDW的斑点都分裂成了两个，这预示着ICDW可能是由不同CDW的相移形成的(ICDW state with domains may be created by a simple phase shift of CCDW between domains)

![选区_319](/home/cris/图片/截图/选区_319.png)

同时他们实验中可以用STM探针移开铜原子而且发现畴壁结构可以被STM高偏压微扰。下图中图a是Cu插层之后用探针把Cu原子移开得到的结构，图b是对应的傅里叶变换的图，图c是由黄圈圈中的斑点做逆傅里叶变换得到的pattern。可以看到

对图a中的结构施加-350mV的偏压就得到图d，图d中的黄线圈起来的部分就是他们施加偏压得到的畴壁，畴壁结构对应的其实是一种拓扑缺陷，可以看到在畴壁结构中CDW斑点分裂为2个，对这些斑点做逆傅里叶变换得到的f图，同时看上面插层结构对应的STS可以得到，在畴壁结构中费米面附近有一个更多的费米子(DWs host an extra population of fermions)

![选区_321](/home/cris/图片/截图/选区_321.png)

随后为了研究CDW可能的机制，他们使用了FT和STS 相结合的技术，先在一个偏压下测一张STS谱，然后对它做傅里叶变换，在通过傅里叶变换中的峰位确定动量信息从而得到色散关系。因为铜原子会造成噪声，所以他们把铜原子移除了，并表示移除之后STS谱仍然几乎保持不变。

![选区_322](/home/cris/图片/截图/选区_322.png)

作者认为电子doping到Ti-3d带应该会导致激子贡献减小，但是电声耦合的作用不受影响。所以认为电声耦合相互作用在ICDW形成上占据主导作用。

------

### Reproduction of the Charge Density Wave Phase Diagram in 1T-TiSe2 Exposes its Excitonic Character

By  Chuan Chen $et. al.$ PhysRevLett.121.226602(2018)





