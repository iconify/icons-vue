<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGfjVXb)"><path fill="url(#iI91N8c)" clip-rule="evenodd" class="k-3sc5bjb"/><path fill="url(#iKFWypy)" clip-rule="evenodd" class="k-3sc5bjb"/><path fill="url(#iGB58id)" clip-rule="evenodd" class="k-3sc5bjb"/><path fill="url(#iqMOsyc)" clip-rule="evenodd" class="k-3sc5bjb"/><path fill="url(#ihvo6qc)" clip-rule="evenodd" class="k-3sc5bjb"/><path fill="url(#i1RU65b)" clip-rule="evenodd" class="k-3sc5bjb"/><path fill="url(#ioIikJe)" clip-rule="evenodd" class="k-3sc5bjb"/><path fill="url(#iWNEPhc)" clip-rule="evenodd" class="k-3sc5bjb"/><path fill="url(#iRogtGi)" clip-rule="evenodd" class="k-3sc5bjb"/><path fill="url(#iOEYvFR)" clip-rule="evenodd" class="k-3sc5bjb"/><path fill="url(#i76csWd)" clip-rule="evenodd" class="k-3sc5bjb"/><path fill="url(#iZotIjb)" clip-rule="evenodd" class="k-3sc5bjb"/></g><path fill="url(#i08HAYo)" class="rihmkq8le"/><path fill="url(#ixLFgme)" class="rihmkq8le"/><path fill="url(#iRNOrCe)" class="f3ael5nnj"/><path fill="url(#izlspBK)" class="f3ael5nnj"/><path fill="url(#i3kJV0d)" class="f3ael5nnj"/><path fill="url(#iFGqZ7b)" class="aja9ggbky"/><path fill="url(#intQq8b)" class="aja9ggbky"/><path fill="url(#iH7QLPe)" class="a1zqpmsoh"/><path fill="url(#ipVLI1y)" class="a1zqpmsoh"/><path fill="url(#i1aP5Bc)" class="a1zqpmsoh"/><path fill="url(#iYuYzlb)" class="i05_9_uff"/><path fill="url(#ibXHnbd)" class="i05_9_uff"/><path class="cwhvcxb2p"/><path fill="url(#in3x4bd)" class="julhe_bku"/><path fill="url(#igUtr8b)" class="bkw3kzb2o"/><path fill="url(#iwPt3uy)" class="bkw3kzb2o"/><path fill="url(#iXuTZac)" class="qq72wjb7t"/><path fill="url(#iUiPaud)" class="qq72wjb7t"/><path fill="url(#iwAoUzb)" class="ix2bq6sxv"/><path fill="url(#ijxSbtZ)" class="ix2bq6sxv"/><path fill="url(#isMpOSc)" class="y9-pq0m0d"/><path fill="url(#iNU3sNc)" class="y9-pq0m0d"/><path fill="url(#iCHohDc)" class="y9-pq0m0d"/><path fill="url(#ishXBXd)" class="xx94rur_g"/><path fill="url(#iMgCrRb)" class="io0foab2k"/><g filter="url(#iMPIxWc)"><path class="yb3xpqlqa"/><path fill="url(#irKfYFb)" class="hh61qwr1x"/><path fill="url(#iTaG8bc)" class="hh61qwr1x"/></g><g filter="url(#itfplwe)"><path fill="url(#i3izkpy)" class="fdmt_x0rm"/><path fill="url(#iJ115ec)" class="fdmt_x0rm"/></g><g filter="url(#iezvB3l)"><path class="kg8ku8pkl"/><path fill="url(#iJtQtrc)" class="jniqb-b_t"/></g><g filter="url(#i9QaoPc)"><path fill="url(#iU6iozz)" class="igikzobtj"/></g><path fill="url(#ihuxyNb)" class="vygww6hwx"/><path fill="url(#igTsWse)" class="vygww6hwx"/><path fill="url(#iPIk2Pd)" class="vygww6hwx"/><path fill="url(#icHZoGe)" class="vygww6hwx"/><path fill="url(#iduJ8Qc)" class="vygww6hwx"/><path fill="url(#i9PVYtb)" class="vygww6hwx"/><path fill="url(#i7MGMOd)" class="vygww6hwx"/><path fill="url(#iTednfe)" class="vygww6hwx"/><path fill="url(#iOd8oMc)" class="vygww6hwx"/><g filter="url(#iIUqzyd)"><path class="xtjnb8bha"/></g><g filter="url(#iTcpQId)"><path class="uw7-92b2a"/><path fill="url(#iam4pdd)" class="dt_oc1_oi"/><path fill="url(#i8fXUWb)" class="dt_oc1_oi"/><path fill="url(#iURXt4f)" class="dt_oc1_oi"/><path fill="url(#iRwayJe)" class="dt_oc1_oi"/></g><g filter="url(#igblrLe)"><path fill="url(#iiktKue)" class="u15nt9bft"/></g><g filter="url(#ip0wEXc)"><path stroke="url(#ia5TzJd)" class="dyotvbcyh"/></g><path class="z4ywd65sc"/><g filter="url(#isc6MVd)"><path class="i6_5_8bxg"/></g><g filter="url(#iRa2qcd)"><path class="pvs0l4bkd"/></g><path class="q2i4ibn7g"/><path fill="url(#iciTQIe)" class="cdljqabiv"/><path class="ast24fv_n"/><g filter="url(#ikU36wc)"><path class="n0eu1gbhq"/><path fill="url(#iVpbtgd)" class="th_7jwb-n"/></g><g filter="url(#iV7BQAZ)"><path fill="url(#iSSzvic)" class="hx18usmyi"/></g><path class="ohvfy1wdr"/><path fill="url(#iYAEmRb)" class="qvzg5dqwe"/><path class="nksuw-7zn"/><g filter="url(#iWEiI6m)"><path fill="url(#iflS87r)" class="qlk1a4bgv"/></g><g filter="url(#isEXQjb)"><ellipse transform="rotate(-27.914 13.269 13.296)" class="wz6p55bdg"/><ellipse fill="url(#iVKS8ab)" transform="rotate(-27.914 13.269 13.296)" class="libojgbxm"/></g><path fill="url(#i2Wef1d)" class="yacjacccz"/><path fill="url(#iAvECrc)" class="yacjacccz"/><path fill="url(#iPHUYFd)" class="yacjacccz"/><path fill="url(#iXMTIBb)" class="yacjacccz"/><path fill="url(#iajAx2b)" class="yacjacccz"/><path fill="url(#iXqASBd)" class="yacjacccz"/><path fill="url(#iMLgQTb)" class="yacjacccz"/><path fill="url(#i3tCWcc)" class="yacjacccz"/><g filter="url(#ijJ0O6g)"><path fill="url(#i0JBewd)" class="f-z5vk62h"/><path fill="url(#iA7KXld)" class="f-z5vk62h"/><path fill="url(#iszGV9b)" class="f-z5vk62h"/><path fill="url(#i351hfc)" class="f-z5vk62h"/></g><path fill="url(#iDJTnsb)" class="iv9aw-bqp"/><path fill="url(#ihRfG7d)" class="iv9aw-bqp"/><path fill="url(#iQi1jdd)" class="iv9aw-bqp"/><path fill="url(#iRrXLNd)" class="iv9aw-bqp"/><g filter="url(#ixc6erI)"><ellipse class="nt-_wr80m"/></g><defs><radialGradient id="iKFWypy" cx="0" cy="0" r="1" gradientTransform="matrix(-.67685 5.11426 -6.38874 -.84552 15.682 16.879)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iGB58id" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 3.636 10.504)scale(3.90083 5.12539)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iqMOsyc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.755 9.777)scale(2.41433 1.85387)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="ihvo6qc" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 2.17 9.134)scale(2.77646 1.95577)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="i1RU65b" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 1.87 12.509)scale(3.3137 4.59993)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="ioIikJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6169 1.61702 -2.25975 -2.2596 22.564 7.365)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iWNEPhc" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.288 8.3)scale(2.15391 4.49182)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iRogtGi" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.84 9.94)scale(3.25593 4.14757)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iOEYvFR" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01458 -2.973 2.35146 -.80247 21.33 10.388)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="i76csWd" cx="0" cy="0" r="1" gradientTransform="rotate(5.988 -120.452 93.83)scale(1.69631 2.74851)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="iZotIjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9401 -4.15533 1.49974 -.3393 21.756 12.347)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="i08HAYo" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.59375 -5.6138 0 16.011 20.61)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="cr7yd6bcj"/><stop offset="1" class="mv_v0947c"/></radialGradient><radialGradient id="ixLFgme" cx="0" cy="0" r="1" gradientTransform="matrix(-.96875 0 0 -5.28125 18.483 26.172)" gradientUnits="userSpaceOnUse"><stop class="ke__lf9po"/><stop offset="1" class="i5rrmccaf"/></radialGradient><radialGradient id="iRNOrCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.91396 -1.61702 0 13.721 24.564)" gradientUnits="userSpaceOnUse"><stop class="dr2x31jzv"/><stop offset="1" class="omeu62b7c"/></radialGradient><radialGradient id="izlspBK" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55816 -.70149 0 13.721 26.231)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="rrfndackx"/><stop offset="1" class="e3j7-mb6u"/></radialGradient><radialGradient id="i3kJV0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5194 3.01929 -4.9325 -2.48219 14.208 20.037)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="ez-c7ubrp"/><stop offset="1" class="mzrwpxbna"/></radialGradient><radialGradient id="iFGqZ7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -2.83386 0 20.042 20.266)" gradientUnits="userSpaceOnUse"><stop class="grpyt1-9k"/><stop offset="1" class="p-n74xx1h"/></radialGradient><radialGradient id="intQq8b" cx="0" cy="0" r="1" gradientTransform="matrix(.88171 0 0 11.0473 18.279 27.384)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wwty3-ban"/><stop offset="1" class="a41x9tbei"/></radialGradient><radialGradient id="ipVLI1y" cx="0" cy="0" r="1" gradientTransform="matrix(-3.52726 -8.45621 9.64626 -4.02365 12.416 28.884)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sqvmrgb3n"/><stop offset=".951" class="xnbb4159v"/></radialGradient><radialGradient id="i1aP5Bc" cx="0" cy="0" r="1" gradientTransform="matrix(.13057 0 0 9.00654 8.341 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="jiob30meo"/><stop offset="1" class="v2x6yq-ng"/></radialGradient><radialGradient id="iYuYzlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.78322 -2.01004 0 23.659 22.543)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="gt-qelr6u"/><stop offset="1" class="xmtd48u_j"/></radialGradient><radialGradient id="ibXHnbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -.27856 0 23.659 27.937)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="thq31dj-g"/><stop offset="1" class="qf92jxbjd"/></radialGradient><radialGradient id="in3x4bd" cx="0" cy="0" r="1" gradientTransform="rotate(-108.091 18.473 10.12)scale(11.6646 18.6686)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="yrdgovb8a"/><stop offset=".971" class="f2js-baog"/></radialGradient><radialGradient id="iwPt3uy" cx="0" cy="0" r="1" gradientTransform="matrix(1.79395 -5.21875 8.06034 2.77074 19.24 25.36)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="juo63cbvd"/><stop offset=".998" class="o2jd-jggt"/></radialGradient><radialGradient id="iXuTZac" cx="0" cy="0" r="1" gradientTransform="matrix(1.87 -7.3125 2.94555 .75325 6.471 28.89)" gradientUnits="userSpaceOnUse"><stop class="ecitxobgm"/><stop offset="1" class="rk8_jsb0a"/></radialGradient><radialGradient id="iwAoUzb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2124 -8.20544 2.09119 -.30899 25.529 29.93)" gradientUnits="userSpaceOnUse"><stop class="wqe5m4buq"/><stop offset="1" class="zykt_9b7s"/></radialGradient><radialGradient id="ijxSbtZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32422 .46978 0 23.659 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="cs69zqbom"/><stop offset="1" class="u77xpkbsk"/></radialGradient><radialGradient id="isMpOSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09685 -3.968 0 16.021 20.59)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="e6b_v3oow"/><stop offset=".88" class="dwvgclbly"/></radialGradient><radialGradient id="iNU3sNc" cx="0" cy="0" r="1" gradientTransform="rotate(124.232 3.699 15.26)scale(3.11083 1.51803)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="r0oe3abav"/><stop offset="1" class="ktbu0qmwq"/></radialGradient><radialGradient id="iCHohDc" cx="0" cy="0" r="1" gradientTransform="rotate(150.285 5.654 12.362)scale(3.04044 5.42348)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="wugfrnb2x"/><stop offset="1" class="cmog0k4qk"/></radialGradient><radialGradient id="irKfYFb" cx="0" cy="0" r="1" gradientTransform="rotate(151.74 3.718 7.459)scale(2.40091 1.74395)" gradientUnits="userSpaceOnUse"><stop class="fstpegb9p"/><stop offset="1" class="j_0-ovbct"/></radialGradient><radialGradient id="iTaG8bc" cx="0" cy="0" r="1" gradientTransform="rotate(-139.654 8.179 6.006)scale(1.88468)" gradientUnits="userSpaceOnUse"><stop class="wdxnqtb0s"/><stop offset="1" class="sokto328j"/></radialGradient><radialGradient id="i3izkpy" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 43.973 -40.498)scale(3.06706 3.74474)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iJ115ec" cx="0" cy="0" r="1" gradientTransform="matrix(1.35377 0 0 .58287 21.715 12.16)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iJtQtrc" cx="0" cy="0" r="1" gradientTransform="matrix(1.69376 -.126 .09849 1.32404 21.095 14.2)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="iU6iozz" cx="0" cy="0" r="1" gradientTransform="matrix(-.98062 -.06486 .10505 -1.58824 10.39 14.074)" gradientUnits="userSpaceOnUse"><stop class="skawyi4wg"/><stop offset="1" class="m4_7atb5f"/></radialGradient><radialGradient id="ihuxyNb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.136 8.845)scale(8.03385 10.7532)" gradientUnits="userSpaceOnUse"><stop class="bh-hnbo7n"/><stop offset="1" class="lpta13m6o"/></radialGradient><radialGradient id="igTsWse" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.599 9.131)scale(2.67209 1.8608)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iPIk2Pd" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 21.136 1)scale(4.63795 5.88469)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="icHZoGe" cx="0" cy="0" r="1" gradientTransform="scale(10.594 8.47528)rotate(90 .012 1.5)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="itwv69uqh"/><stop offset="1" class="fhh-awool"/></radialGradient><radialGradient id="iduJ8Qc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.277 8.583)scale(7.89435 13.5916)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="i9PVYtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.2909 1.58429 0 18.603 13.001)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="i7MGMOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.47234 1.6874 0 13.692 12.745)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iTednfe" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 4.802 11.932)scale(3.74898 2.9998)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iOd8oMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.84375 -9.18235 0 16.021 12.024)" gradientUnits="userSpaceOnUse"><stop offset=".119" class="u3p_p-cpd"/><stop offset="1" class="za_j2jl3p"/></radialGradient><radialGradient id="iam4pdd" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 14.657 .968)scale(2.34917 .72399)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iRwayJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.87431 0 0 -.24443 16.632 15.723)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iciTQIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .91011 -1.44764 0 18.469 13.404)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iVpbtgd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26016 -.33525 .46156 -.35817 18.213 13.498)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYAEmRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .91012 -1.44764 0 13.573 13.404)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iVKS8ab" cx="0" cy="0" r="1" gradientTransform="matrix(-.00868 -.55422 .6662 -.01043 13.252 13.65)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2Wef1d" cx="0" cy="0" r="1" gradientTransform="rotate(89.9 6.196 13.391)scale(4.18751 2.64389)" gradientUnits="userSpaceOnUse"><stop class="qq6id-bgn"/><stop offset="1" class="o043sbvrw"/></radialGradient><radialGradient id="iAvECrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16 5.79775 0 11.834 9.86)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="lsejgobiz"/><stop offset="1" class="ufkfu5bhx"/></radialGradient><radialGradient id="iPHUYFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -8 15.26892 2.44541 17.24 10.297)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="g4-w6ccdn"/><stop offset=".946" class="dan8ctbrb"/></radialGradient><radialGradient id="iXMTIBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.875 -.59037 0 13.177 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="ms9ao5bgb"/><stop offset="1" class="gdbdqk9_y"/></radialGradient><radialGradient id="iajAx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.37503 4.21874 -1.6853 .14982 13.302 2.703)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="x8to7on4z"/><stop offset="1" class="x2t1gbbxv"/></radialGradient><radialGradient id="iXqASBd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24995 -6.37504 7.8363 -6.45332 16.74 9.703)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="oobbay99s"/><stop offset="1" class="hb0fg9dnu"/></radialGradient><radialGradient id="i3tCWcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59375 5.79687 0 10.959 10.094)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="aa5l6qb6a"/><stop offset="1" class="mgd_z41tu"/></radialGradient><radialGradient id="iszGV9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.0625 1 0 13.459 9.86)" gradientUnits="userSpaceOnUse"><stop class="lmg939n4j"/><stop offset="1" class="psulmw2ur"/></radialGradient><radialGradient id="i351hfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.78125 1.6875 0 18.334 9.922)" gradientUnits="userSpaceOnUse"><stop class="kyytyn57f"/><stop offset="1" class="xr07nxbnn"/></radialGradient><radialGradient id="iRrXLNd" cx="0" cy="0" r="1" gradientTransform="matrix(.52313 2.06026 -12.32015 3.12823 11.697 8.935)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="nrsb-h28d"/><stop offset="1" class="j07dbhb1v"/></radialGradient><linearGradient id="iI91N8c" x1="21.286" x2="14.404" y1="6.274" y2="18.345" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iH7QLPe" x1="9.158" x2="9.158" y1="21.199" y2="29.929" gradientUnits="userSpaceOnUse"><stop class="u14do7mcv"/><stop offset="1" class="qo0y3qb-y"/></linearGradient><linearGradient id="igUtr8b" x1="21.034" x2="21.034" y1="19.735" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="di--38mzt"/><stop offset="1" class="htellnhxv"/></linearGradient><linearGradient id="iUiPaud" x1="8.468" x2="6.8" y1="29.929" y2="29.769" gradientUnits="userSpaceOnUse"><stop offset=".333" class="x43wds7fi"/><stop offset="1" class="xjs932baa"/></linearGradient><linearGradient id="ishXBXd" x1="7.961" x2="24.088" y1="19.662" y2="19.662" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iMgCrRb" x1="7.961" x2="24.088" y1="19.628" y2="19.628" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i8fXUWb" x1="14.968" x2="16.021" y1="15.567" y2="15.567" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iURXt4f" x1="16.021" x2="16.021" y1="16.36" y2="15.657" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iiktKue" x1="16.021" x2="16.168" y1="13.273" y2="14.822" gradientUnits="userSpaceOnUse"><stop class="h20bv1b0q"/><stop offset="1" class="p4urpobhi"/></linearGradient><linearGradient id="ia5TzJd" x1="14.827" x2="15.344" y1="18.045" y2="17.246" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iSSzvic" x1="19.341" x2="18.989" y1="13.464" y2="13.681" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iflS87r" x1="14.408" x2="14.056" y1="13.464" y2="13.681" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMLgQTb" x1="9.771" x2="10.584" y1="9.234" y2="9.234" gradientUnits="userSpaceOnUse"><stop class="ms43e0vsz"/><stop offset="1" class="b_iay1xzu"/></linearGradient><linearGradient id="i0JBewd" x1="15.81" x2="15.81" y1="2.07" y2="10.498" gradientUnits="userSpaceOnUse"><stop class="ououd5b1f"/><stop offset="1" class="tl7x7-b-x"/></linearGradient><linearGradient id="iA7KXld" x1="15.81" x2="15.81" y1="2.07" y2="4.672" gradientUnits="userSpaceOnUse"><stop class="ahajb6vmx"/><stop offset="1" class="npjjoacns"/></linearGradient><linearGradient id="iDJTnsb" x1="21.786" x2="5.158" y1="11.243" y2="11.243" gradientUnits="userSpaceOnUse"><stop class="vergo-4jw"/><stop offset="1" class="pj-kb0bjs"/></linearGradient><linearGradient id="ihRfG7d" x1="15.587" x2="15.587" y1="9.842" y2="10.155" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></linearGradient><linearGradient id="iQi1jdd" x1="16.505" x2="16.505" y1="12.148" y2="10.895" gradientUnits="userSpaceOnUse"><stop class="ex-0zhc5k"/><stop offset="1" class="o5ewjjbtz"/></linearGradient><filter id="iGfjVXb" width="17.097" height="17.597" x="7.598" y="3.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2955"/></filter><filter id="iMPIxWc" width="3.76" height="3.61" x="8.719" y="12.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.45098 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2955"/></filter><filter id="itfplwe" width="3.61" height="3.86" x="19.778" y="12.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2955"/></filter><filter id="iezvB3l" width="3.41" height="3.41" x="19.879" y="12.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2955" stdDeviation=".25"/></filter><filter id="i9QaoPc" width="3.11" height="3.11" x="8.991" y="12.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2955" stdDeviation=".175"/></filter><filter id="iIUqzyd" width="3.106" height="4.008" x="14.286" y="13.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2955" stdDeviation=".25"/></filter><filter id="iTcpQId" width="2.606" height="3.508" x="14.718" y="13.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2955" stdDeviation=".125"/></filter><filter id="igblrLe" width="2.606" height="3.508" x="14.718" y="13.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2955" stdDeviation=".125"/></filter><filter id="ip0wEXc" width="4.104" height="1.663" x="13.969" y="16.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2955" stdDeviation=".05"/></filter><filter id="isc6MVd" width="3.343" height="1.442" x="17.102" y="12.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2955"/></filter><filter id="iRa2qcd" width="3.343" height="1.442" x="11.598" y="12.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2955"/></filter><filter id="ikU36wc" width=".858" height=".757" x="17.657" y="12.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2955" stdDeviation=".05"/></filter><filter id="iV7BQAZ" width=".951" height=".976" x="18.612" y="13.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2955" stdDeviation=".1"/></filter><filter id="iWEiI6m" width="1.058" height="1.118" x="13.628" y="12.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2955" stdDeviation=".1"/></filter><filter id="isEXQjb" width="1" height=".766" x="12.769" y="12.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2955" stdDeviation=".05"/></filter><filter id="ijJ0O6g" width="5.791" height="8.428" x="12.915" y="2.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.658824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2955"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2955" result="effect2_innerShadow_4002_2955"/></filter><filter id="ixc6erI" width="7.654" height="2.528" x="15.502" y="9.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2955" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-construction-worker-medium" /></template>
<style>
.a1zqpmsoh {
  d: path("M8.389 22.017a.15.15 0 0 0-.048.11v7.802h1.634v-9.16c-.56.37-1.092.79-1.586 1.248");
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a41x9tbei {
  stop-color: var(--svg-color--f25937, #F25937);
  stop-opacity: 0;
}

.aa5l6qb6a {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ahajb6vmx {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
}

.aja9ggbky {
  d: path("M18.279 19.198c.608.134 1.195.31 1.763.537V29.93H18.28z");
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.ast24fv_n {
  fill: var(--svg-color--000, #000);
  d: path("M17.898 13.87a.57.57 0 0 1 .573-.574a.57.57 0 0 1 .51.838h-1.015a.5.5 0 0 1-.068-.264");
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b_iay1xzu {
  stop-color: var(--svg-color--cdac54, #CDAC54);
  stop-opacity: 0;
}

.bh-hnbo7n {
  stop-color: var(--svg-color--c5957d, #C5957D);
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkw3kzb2o {
  d: path("M22.025 20.77v9.16h-1.983V19.735c.698.28 1.355.62 1.983 1.034");
}

.cdljqabiv {
  d: path("M18.471 12.869a1 1 0 0 1 .965 1.265h-1.934a1.005 1.005 0 0 1 .97-1.265");
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmog0k4qk {
  stop-color: var(--svg-color--8c4d6c, #8C4D6C);
}

.cr7yd6bcj {
  stop-color: var(--svg-color--9d67e1, #9D67E1);
}

.cs69zqbom {
  stop-color: var(--svg-color--8356c7, #8356C7);
}

.cwhvcxb2p {
  fill: var(--svg-color--ffca44, #FFCA44);
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.dan8ctbrb {
  stop-color: var(--svg-color--eecd67, #EECD67);
}

.di--38mzt {
  stop-color: var(--svg-color--ffda42, #FFDA42);
}

.dr2x31jzv {
  stop-color: var(--svg-color--ff7446, #FF7446);
}

.dt_oc1_oi {
  d: path("m15.592 13.668l-.596 1.907a.605.605 0 0 0 .584.785h.882a.607.607 0 0 0 .584-.785l-.596-1.907c-.128-.422-.724-.422-.858 0");
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.dwvgclbly {
  stop-color: var(--svg-color--a36976, #A36976);
}

.dyotvbcyh {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.021 17.34c-.584 0-1.133-.14-1.595-.387c-.157-.082-.327.1-.227.246a2.167 2.167 0 0 0 3.645 0c.099-.152-.07-.328-.228-.246a3.4 3.4 0 0 1-1.595.387Z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3j7-mb6u {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
  stop-opacity: 0;
}

.e6b_v3oow {
  stop-color: var(--svg-color--98596f, #98596F);
}

.ecitxobgm {
  stop-color: var(--svg-color--966ce3, #966CE3);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.ex-0zhc5k {
  stop-color: var(--svg-color--e1926f, #E1926F);
}

.ez-c7ubrp {
  stop-color: var(--svg-color--da4708, #DA4708);
}

.f-z5vk62h {
  d: path("M14.615 2.07h2.39c.829 0 1.5.603 1.5 1.633v6.795h-5.39V3.703c0-1.03.671-1.633 1.5-1.633");
}

.f2js-baog {
  stop-color: var(--svg-color--cd963a, #CD963A);
}

.f3ael5nnj {
  d: path("M13.721 19.198c-.608.134-1.196.31-1.763.537V29.93h1.763z");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fdmt_x0rm {
  d: path("M21.583 15.879a1.805 1.805 0 1 0 0-3.61a1.805 1.805 0 0 0 0 3.61");
}

.fhh-awool {
  stop-color: var(--svg-color--995275, #995275);
}

.fstpegb9p {
  stop-color: var(--svg-color--744230, #744230);
}

.ft5dv1b6b {
  fill: none;
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g4-w6ccdn {
  stop-color: var(--svg-color--eecd67, #EECD67);
  stop-opacity: 0;
}

.gdbdqk9_y {
  stop-color: var(--svg-color--e1b037, #E1B037);
  stop-opacity: 0;
}

.grpyt1-9k {
  stop-color: var(--svg-color--ff7523, #FF7523);
}

.gt-qelr6u {
  stop-color: var(--svg-color--ff905a, #FF905A);
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h20bv1b0q {
  stop-color: var(--svg-color--a06f6b, #A06F6B);
}

.hb0fg9dnu {
  stop-color: var(--svg-color--c3a852, #C3A852);
}

.hh61qwr1x {
  d: path("M10.524 15.879a1.805 1.805 0 1 0 0-3.61a1.805 1.805 0 0 0 0 3.61");
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.htellnhxv {
  stop-color: var(--svg-color--ffcf4c, #FFCF4C);
}

.hx18usmyi {
  d: path("M19.363 13.738a.94.94 0 0 0-.26-.519l-.291.32l.131.256z");
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i05_9_uff {
  d: path("M23.627 22.032a.1.1 0 0 1 .032.073v7.824h-1.634v-9.16a12.5 12.5 0 0 1 1.602 1.263");
}

.i5rrmccaf {
  stop-color: var(--svg-color--a271ef, #A271EF);
  stop-opacity: 0;
}

.i6_5_8bxg {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.302 13.435c.298-.523.75-.937 1.725-.937c.426 0 .838.118 1.203.414c.302.243.261.555.028.672l-.624.356c-.731-.236-1.54-.268-2.332-.505");
}

.igikzobtj {
  d: path("M10.545 15.279a1.205 1.205 0 1 0 0-2.41a1.205 1.205 0 0 0 0 2.41");
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.io0foab2k {
  d: path("M16.05 19.628h-.046c.112 0 .213 0 .325.012c-.09-.012-.19-.012-.28-.012");
}

.itwv69uqh {
  stop-color: var(--svg-color--9e6476, #9E6476);
  stop-opacity: 0;
}

.iv9aw-bqp {
  d: path("M22.266 9.842H9.672a1.153 1.153 0 1 0 0 2.306h12.594c.642 0 1.153-.52 1.153-1.153a1.147 1.147 0 0 0-1.153-1.153");
}

.ix2bq6sxv {
  d: path("M27.399 29.93c-.14-.947-.34-1.882-.62-2.787a11.56 11.56 0 0 0-3.12-5.018v7.804z");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_0-ovbct {
  stop-color: var(--svg-color--744230, #744230);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j07dbhb1v {
  stop-color: var(--svg-color--dfb83e, #DFB83E);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jiob30meo {
  stop-color: var(--svg-color--de521d, #DE521D);
}

.jniqb-b_t {
  d: path("M21.584 15.279a1.205 1.205 0 1 0 0-2.41a1.205 1.205 0 0 0 0 2.41");
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.julhe_bku {
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.juo63cbvd {
  stop-color: var(--svg-color--ffce64, #FFCE64);
  stop-opacity: 0;
}

.k-3sc5bjb {
  fill-rule: evenodd;
  d: path("M24.081 15.655a3.64 3.64 0 0 0 .364-1.6c0-.525-.108-1.017-.302-1.465h.006a3.6 3.6 0 0 0-.315-.576l-.003-.003c-.386-.59-1.004-1.054-1.004-1.758l-1.256.104c0-2.044.013-4.045-2.03-4.045a.6.6 0 0 1-.512-.261a3.7 3.7 0 0 0-3.008-1.544a3.7 3.7 0 0 0-3.008 1.544a.64.64 0 0 1-.511.26l-.096.002c-2 .05-2.437 2.032-2.437 4.044H8.801c0 .703-.205 1.063-.59 1.654l-.003.004a3.7 3.7 0 0 0-.247 3.64c.08.159.08.352 0 .51a3.7 3.7 0 0 0-.363 1.579a3.605 3.605 0 0 0 3.61 3.61h9.626a3.605 3.605 0 0 0 3.61-3.61a3.66 3.66 0 0 0-.363-1.578a.58.58 0 0 1 0-.511m-13.753-2.998h-.014L11.66 15.3c.138 3.144 1.365 0 4.362 0s4.304 3.5 4.442.356l1.274-3.587c-.06-1.396-1.072-1.494-1.274-1.494H16.85a4.33 4.33 0 0 1-3.578-1.877a.296.296 0 0 0-.518.057l-.092.218a2.6 2.6 0 0 1-1.334 1.385l-.058.022l-.057.023c-.265.138-.886.55-.909 1.614l.012.344z");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.ke__lf9po {
  stop-color: var(--svg-color--a271ef, #A271EF);
}

.kg8ku8pkl {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M21.584 15.279a1.205 1.205 0 1 0 0-2.41a1.205 1.205 0 0 0 0 2.41");
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktbu0qmwq {
  stop-color: var(--svg-color--b78276, #B78276);
  stop-opacity: 0;
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kyytyn57f {
  stop-color: var(--svg-color--ffe550, #FFE550);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.libojgbxm {
  cx: 13.269px;
  cy: 13.296px;
  rx: 0.437px;
  ry: 0.221px;
}

.lmg939n4j {
  stop-color: var(--svg-color--e3b438, #E3B438);
}

.lpta13m6o {
  stop-color: var(--svg-color--996b68, #996B68);
}

.lsejgobiz {
  stop-color: var(--svg-color--e9b840, #E9B840);
}

.m4_7atb5f {
  stop-color: var(--svg-color--7b4d49, #7B4D49);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgd_z41tu {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
  stop-opacity: 0;
}

.ms43e0vsz {
  stop-color: var(--svg-color--cdac54, #CDAC54);
}

.ms9ao5bgb {
  stop-color: var(--svg-color--d7a439, #D7A439);
}

.mv_v0947c {
  stop-color: var(--svg-color--a473f8, #A473F8);
}

.mzrwpxbna {
  stop-color: var(--svg-color--dc5314, #DC5314);
  stop-opacity: 0;
}

.n0eu1gbhq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.397 13.08c.072.096-.077.212-.247.339s-.295.216-.366.12c-.072-.095.008-.275.177-.402c.17-.127.365-.152.436-.056");
}

.nksuw-7zn {
  fill: var(--svg-color--000, #000);
  d: path("M14.144 13.87a.57.57 0 0 0-.573-.574a.57.57 0 0 0-.51.838h1.015a.6.6 0 0 0 .068-.264");
}

.npjjoacns {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
  stop-opacity: 0;
}

.nrsb-h28d {
  stop-color: var(--svg-color--c4a966, #C4A966);
}

.nt-_wr80m {
  cx: 19.329px;
  cy: 10.856px;
  fill: var(--svg-color--fff060, #FFF060);
  rx: 2.827px;
  ry: 0.264px;
}

.o043sbvrw {
  stop-color: var(--svg-color--fd4, #FD4);
}

.o2jd-jggt {
  stop-color: var(--svg-color--ffce64, #FFCE64);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ewjjbtz {
  stop-color: var(--svg-color--f9b14d, #F9B14D);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohvfy1wdr {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.339 12.564c-.733 0-1.352.505-1.52 1.188c-.05.195.1.382.3.382h2.503c.16 0 .287-.146.255-.305a1.57 1.57 0 0 0-1.538-1.265");
}

.omeu62b7c {
  stop-color: var(--svg-color--ff6f4e, #FF6F4E);
}

.oobbay99s {
  stop-color: var(--svg-color--c3a852, #C3A852);
  stop-opacity: 0;
}

.ououd5b1f {
  stop-color: var(--svg-color--f9cd2e, #F9CD2E);
}

.p-n74xx1h {
  stop-color: var(--svg-color--fb684a, #FB684A);
}

.p4urpobhi {
  stop-color: var(--svg-color--a06f6b, #A06F6B);
  stop-opacity: 0;
}

.pj-kb0bjs {
  stop-color: var(--svg-color--f0bc33, #F0BC33);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psulmw2ur {
  stop-color: var(--svg-color--e3b438, #E3B438);
  stop-opacity: 0;
}

.pvs0l4bkd {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M14.74 13.435c-.298-.523-.75-.937-1.724-.937a1.86 1.86 0 0 0-1.204.414c-.301.243-.261.555-.027.672l.623.356c.731-.236 1.54-.268 2.332-.505");
}

.q2i4ibn7g {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.703 12.564c.733 0 1.352.505 1.52 1.188c.05.195-.1.382-.3.382H17.42a.258.258 0 0 1-.255-.305a1.57 1.57 0 0 1 1.538-1.265");
}

.qf92jxbjd {
  stop-color: var(--svg-color--fe713a, #FE713A);
  stop-opacity: 0;
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qlk1a4bgv {
  d: path("M14.486 13.752c0-.323-.264-.539-.335-.604l-.323.313l.199.405z");
}

.qo0y3qb-y {
  stop-color: var(--svg-color--f46d40, #F46D40);
}

.qq6id-bgn {
  stop-color: var(--svg-color--ffee61, #FFEE61);
}

.qq72wjb7t {
  d: path("M4.601 29.93c.14-.947.34-1.882.62-2.787a11.56 11.56 0 0 1 3.12-5.018v7.804z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qvzg5dqwe {
  d: path("M13.571 12.869a1 1 0 0 0-.965 1.265h1.934q.036-.129.037-.264a1.01 1.01 0 0 0-1.006-1.001");
}

.r0oe3abav {
  stop-color: var(--svg-color--b78276, #B78276);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.rihmkq8le {
  d: path("M16.021 19.32c-.78 0-1.55.08-2.3.23v10.38h4.58V19.55c-.74-.15-1.5-.23-2.28-.23");
}

.rk8_jsb0a {
  stop-color: var(--svg-color--8d6fbf, #8D6FBF);
}

.rrfndackx {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
}

.skawyi4wg {
  stop-color: var(--svg-color--754b4e, #754B4E);
}

.sokto328j {
  stop-color: var(--svg-color--884e66, #884E66);
  stop-opacity: 0;
}

.sqvmrgb3n {
  stop-color: var(--svg-color--e07241, #E07241);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.t_t6-ha7d {
  stop-color: var(--svg-color--ffd131, #FFD131);
  stop-opacity: 0;
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.th_7jwb-n {
  d: path("M18.397 13.08c.072.096-.077.212-.247.339s-.295.216-.366.12c-.072-.095.008-.275.177-.402c.17-.127.365-.152.436-.056");
}

.thq31dj-g {
  stop-color: var(--svg-color--fe713a, #FE713A);
}

.tl7x7-b-x {
  stop-color: var(--svg-color--ffca3d, #FFCA3D);
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u14do7mcv {
  stop-color: var(--svg-color--e6743e, #E6743E);
}

.u15nt9bft {
  d: path("m15.592 13.59l-.596 1.907a.605.605 0 0 0 .584.784h.882a.607.607 0 0 0 .584-.784l-.596-1.907c-.128-.423-.724-.423-.858 0");
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u3p_p-cpd {
  stop-color: var(--svg-color--8b535c, #8B535C);
}

.u77xpkbsk {
  stop-color: var(--svg-color--8356c7, #8356C7);
  stop-opacity: 0;
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ufkfu5bhx {
  stop-color: var(--svg-color--e9b840, #E9B840);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.uw7-92b2a {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.592 13.668l-.596 1.907a.605.605 0 0 0 .584.785h.882a.607.607 0 0 0 .584-.785l-.596-1.907c-.128-.422-.724-.422-.858 0");
}

.v2x6yq-ng {
  stop-color: var(--svg-color--de521d, #DE521D);
  stop-opacity: 0;
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vergo-4jw {
  stop-color: var(--svg-color--ffe24a, #FFE24A);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vygww6hwx {
  d: path("M10.305 12.016c.023-1.064.644-1.476.909-1.614l.057-.022l.058-.023a2.58 2.58 0 0 0 1.334-1.385l.092-.218a.296.296 0 0 1 .518-.057a4.33 4.33 0 0 0 3.578 1.877h3.612c.202 0 1.214.098 1.274 1.495l-.133 3.447c-.139 3.144-2.594 5.255-5.59 5.255s-5.452-2.111-5.59-5.255z");
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wdxnqtb0s {
  stop-color: var(--svg-color--884e66, #884E66);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wqe5m4buq {
  stop-color: var(--svg-color--b087fd, #B087FD);
}

.wugfrnb2x {
  stop-color: var(--svg-color--8c4d6c, #8C4D6C);
  stop-opacity: 0;
}

.wwty3-ban {
  stop-color: var(--svg-color--f25937, #F25937);
}

.wz6p55bdg {
  cx: 13.269px;
  cy: 13.296px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.437px;
  ry: 0.221px;
}

.x2t1gbbxv {
  stop-color: var(--svg-color--cba731, #CBA731);
  stop-opacity: 0;
}

.x43wds7fi {
  stop-color: var(--svg-color--735992, #735992);
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x8to7on4z {
  stop-color: var(--svg-color--b59741, #B59741);
}

.xjs932baa {
  stop-color: var(--svg-color--735992, #735992);
  stop-opacity: 0;
}

.xmtd48u_j {
  stop-color: var(--svg-color--ff7955, #FF7955);
}

.xnbb4159v {
  stop-color: var(--svg-color--cc6e42, #CC6E42);
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xr07nxbnn {
  stop-color: var(--svg-color--ffe550, #FFE550);
  stop-opacity: 0;
}

.xsg9vwb1s {
  stop-color: var(--svg-color--ffd131, #FFD131);
}

.xtjnb8bha {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.58 13.824l-.766 1.907a.605.605 0 0 0 .584.784h.882a.607.607 0 0 0 .584-.784l-.596-1.907c-.128-.423-.554-.423-.687 0");
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xx94rur_g {
  d: path("M16.42 19.628c.28.012.571.034.863.056c-.292-.022-.572-.044-.864-.056");
}

.y9-pq0m0d {
  d: path("M13.81 20.295c.06.798.585 2.392 2.211 2.392s2.151-1.594 2.211-2.392z");
}

.yacjacccz {
  d: path("M9.771 7.178a4.1 4.1 0 0 1 4.1-4.1h3.988a4.1 4.1 0 0 1 4.1 4.1V9.86H9.77z");
}

.yb3xpqlqa {
  fill: var(--svg-color--885f59, #885F59);
  d: path("M10.524 15.879a1.805 1.805 0 1 0 0-3.61a1.805 1.805 0 0 0 0 3.61");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.yrdgovb8a {
  stop-color: var(--svg-color--fdbf28, #FDBF28);
  stop-opacity: 0;
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.z4ywd65sc {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.021 17.34c-.584 0-1.133-.14-1.595-.387c-.157-.082-.327.1-.227.246a2.167 2.167 0 0 0 3.645 0c.099-.152-.07-.328-.228-.246a3.4 3.4 0 0 1-1.595.387");
}

.za_j2jl3p {
  stop-color: var(--svg-color--8b535c, #8B535C);
  stop-opacity: 0;
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zykt_9b7s {
  stop-color: var(--svg-color--9879c9, #9879C9);
}

</style>
