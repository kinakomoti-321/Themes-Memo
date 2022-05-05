# ManifoldNextEventEstimation
MNEEはSDSパスなどでできるCausticsをうまいこと出す手法。話としてはニュートン法を使ってうまくパスをずらし、寄与が高いパスを探索するらしい。
現論文と思われるものはこれ
- (Minifold Next Event Estimation)[https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.12681]
恐らくこれに沿って作られたスライドもある
- (MNEE slide)[https://jo.dreggn.org/home/2015_mnee_talk.pdf]

BlenderでMNEEの実装がなされて3.2(beta?)でcausticsができるようになったらしい
- (youtube)[https://www.youtube.com/watch?v=o-Twi-H2M8g&ab_channel=MarioHawat]

Developer向けのフォーラムでMNEEのことについて述べられている
- https://developer.blender.org/D13533

一応なんか高周波Cuasticsに対する論文も出てるらしい(具体的な手法は不明)
- https://rgl.epfl.ch/publications/Zeltner2020Specular

MNEEは一応前身としてMLTの手法の一つにあったらしい。
→MLTは既存のレンダラーに組み込みにくいからあんまり採用されなかった？

