<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#id3V7ib)"><path class="xjfgv-bnu"/><path fill="url(#iJRf5ve)" class="mxt8fccfn"/></g><path fill="url(#iwzihEb)" class="rbv2mhb1n"/><path fill="url(#iUWyfvy)" class="rbv2mhb1n"/><path fill="url(#iilgkNc)" class="keegem7ly"/><path fill="url(#i6s8fUc)" class="keegem7ly"/><path fill="url(#iZ5WhAd)" class="n7v132bzw"/><path fill="url(#i79PCzd)" class="n7v132bzw"/><path fill="url(#izWRixE)" class="n7v132bzw"/><path fill="url(#iVTNAFd)" class="n7v132bzw"/><path fill="url(#iZEqgFe)" class="yfvv7-pgl"/><path fill="url(#if0UVWc)" class="yfvv7-pgl"/><path fill="url(#iiPCr1U)" class="yfvv7-pgl"/><path fill="url(#ii4kZLd)" class="yfvv7-pgl"/><path fill="url(#iX0ccme)" class="yfvv7-pgl"/><path fill="url(#iQmngve)" class="jmqc0ac7y"/><path fill="url(#i1mwDmb)" class="zdbcebemm"/><path fill="url(#iXnq14c)" class="csxoxoo5l"/><path fill="url(#iDaNLBd)" class="lnw18-bme"/><path fill="url(#imih2be)" class="lnw18-bme"/><path fill="url(#iaifHBY)" class="lnw18-bme"/><path fill="url(#i2zysTc)" class="kfasd4a1w"/><path fill="url(#iwzcNhy)" class="kfasd4a1w"/><path fill="url(#icZB7gd)" class="w0st2glnz"/><path fill="url(#iZ63QxM)" class="w0st2glnz"/><path fill="url(#i23qVDd)" class="w0st2glnz"/><path fill="url(#iAVESGc)" class="w0st2glnz"/><g filter="url(#iE65LUT)"><path fill="url(#iPOWwZb)" class="h1qr0p-pz"/><path fill="url(#i5xVnnM)" class="h1qr0p-pz"/><path fill="url(#ieqPEld)" class="h1qr0p-pz"/></g><path fill="url(#iv0nzLc)" class="v4t_cwbem"/><path fill="url(#idIxI5c)" class="v4t_cwbem"/><path fill="url(#izXqsfd)" class="v4t_cwbem"/><g filter="url(#iCuMYSc)"><path fill="url(#in9D37C)" class="ke6r5xbfo"/></g><g filter="url(#ijodwZb)"><circle fill="url(#iXVKjoe)" class="g04s-nsls"/></g><g filter="url(#ikbW4Yd)"><circle fill="url(#itnqXmw)" class="jybffqyvj"/></g><g filter="url(#iN5BQLc)"><path fill="url(#i1OyRuf)" class="zx87c8buv"/><path fill="url(#iSc5sSc)" class="zx87c8buv"/><path fill="url(#iLgkWPt)" class="zx87c8buv"/><path fill="url(#iTpjkAd)" class="zx87c8buv"/><path fill="url(#i2C6icf)" class="zx87c8buv"/></g><g filter="url(#iNLZ08c)"><path stroke="url(#ijtpuMe)" class="m71o8sbbb"/></g><g filter="url(#iy8xRbe)"><path stroke="url(#i3iTTLc)" class="rkgfshb2k"/></g><g filter="url(#iMqneUd)"><path stroke="url(#ijoyhQe)" class="djc5ph3fa"/></g><path fill="url(#ijRE5Rc)" class="efd79xblx"/><path fill="url(#izzacne)" class="rokcf0btl"/><g filter="url(#iTZsqUr)"><path fill="url(#iBFYhud)" class="u6064t8zh"/><path fill="url(#ioqe5PF)" class="u6064t8zh"/></g><path fill="url(#i7EbdYh)" class="u6064t8zh"/><path fill="url(#ihCGABd)" class="u6064t8zh"/><path fill="url(#iVutCPQ)" class="u6064t8zh"/><path fill="url(#i3NKwHb)" class="u6064t8zh"/><path fill="url(#i3qmljd)" class="u6064t8zh"/><path fill="url(#iWqBnzc)" class="u6064t8zh"/><path fill="url(#iaa28gT)" class="u6064t8zh"/><path fill="url(#iLwUPGc)" class="u6064t8zh"/><g filter="url(#ithrQNb)"><path class="lys-m0b9d"/></g><g filter="url(#i5JwX9c)"><path class="e-coa4boh"/><path fill="url(#iLSrYId)" class="j2psesb3q"/><path fill="url(#i8vglTc)" class="j2psesb3q"/><path fill="url(#ivCDNXd)" class="j2psesb3q"/><path fill="url(#irfHK1d)" class="j2psesb3q"/><path fill="url(#iPyKhId)" class="j2psesb3q"/></g><path fill="url(#iNr0Xge)" class="j2psesb3q"/><path fill="url(#iG4JCub)" class="j2psesb3q"/><path fill="url(#iPA5XNd)" class="nnbtyr9mx"/><path fill="url(#isQeZnb)" class="nnbtyr9mx"/><g filter="url(#iHn27bc)"><path stroke="url(#i3DWtSd)" class="urb_bmb5c"/></g><path fill="url(#ibsBrib)" class="usejpb1rc"/><g filter="url(#iPJsEld)"><path fill="url(#ihbmcue)" class="czkqlgk-l"/></g><path fill="url(#i1vZIBc)" class="czkqlgk-l"/><path fill="url(#ik4JgPe)" class="czkqlgk-l"/><path fill="url(#iqI2Pjb)" class="czkqlgk-l"/><g filter="url(#iLPEZit)"><path class="uzyno4b9g"/></g><g filter="url(#iAWw0Kd)"><path class="pqv2eiavf"/></g><g filter="url(#iJ4nmEe)"><path class="vktvlibck"/><path fill="url(#i8AaFsc)" class="l6cm_-bda"/><path fill="url(#iNpvKsd)" class="l6cm_-bda"/></g><g filter="url(#imsr8Bb)"><path class="a7vxm9bsf"/><path fill="url(#icFzY4c)" class="x-k68jb_j"/><path fill="url(#iNo0Ygf)" class="x-k68jb_j"/><path fill="url(#iyuiK3d)" class="x-k68jb_j"/></g><path class="qhd9kobac"/><path fill="url(#iBhxRfb)" class="m5ccv-bud"/><path class="obn84gbyd"/><g filter="url(#ieyy4Cb)"><path class="l-omnpbuk"/><path fill="url(#i2hrT5Q)" class="ci5sdgbnv"/></g><g filter="url(#iHmmY5q)"><path fill="url(#itry7kc)" class="l5l7f-yex"/></g><path class="fmhio103w"/><path fill="url(#i2YbMqd)" class="vzfrs2boh"/><path class="z3s-bsbfl"/><g filter="url(#iHzC8Vb)"><path fill="url(#iT614la)" class="abxpw76-t"/></g><g filter="url(#iQFffmc)"><ellipse transform="rotate(-27.914 12.644 11.33)" class="z9s_-ergi"/><ellipse fill="url(#ieJstKJ)" transform="rotate(-27.914 12.644 11.33)" class="u3pl8_5vo"/></g><path fill="url(#iBawrDe)" class="za-e59biz"/><path fill="url(#ioR5Gmc)" class="za-e59biz"/><path fill="url(#iHhovZb)" class="za-e59biz"/><path fill="url(#iIFQPxc)" class="za-e59biz"/><path fill="url(#ipczPke)" class="nuwn-flsy"/><path fill="url(#i85wCKc)" class="nuwn-flsy"/><g filter="url(#iwa9FLb)"><path fill="url(#iEfdNae)" class="b6nw53xek"/></g><g filter="url(#i6Xhrsc)"><path fill="url(#isIdhye)" class="g_w780bgb"/></g><g filter="url(#ivqX26K)"><path class="yw8aqm-as"/></g><g filter="url(#i4ATRPe)"><path class="mbqhfeswf"/></g><g filter="url(#iMgZLBe)"><path class="c1345jbbi"/></g><defs><radialGradient id="iwzihEb" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.708 25.604)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="iilgkNc" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.67 19.541)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="izWRixE" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71872 5.59376 -.25587 -.12436 24.239 17.886)" gradientUnits="userSpaceOnUse"><stop class="mnp72frot"/><stop offset="1" class="l4rg4-bid"/></radialGradient><radialGradient id="if0UVWc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.597 18.157 8.925)scale(6.81742 .9881)" gradientUnits="userSpaceOnUse"><stop class="rzqjthgas"/><stop offset="1" class="ejynn6b3w"/></radialGradient><radialGradient id="ii4kZLd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.80897 .6578 -1.95135 -5.36624 12.187 17.77)" gradientUnits="userSpaceOnUse"><stop class="i03-jcbks"/><stop offset="1" class="m27qtcbgg"/></radialGradient><radialGradient id="iDaNLBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50857 -5.52096 0 15.106 20.252)" gradientUnits="userSpaceOnUse"><stop offset=".092" class="cn088_52m"/><stop offset=".838" class="nym90gb4n"/></radialGradient><radialGradient id="imih2be" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.08205 11.2731 0 15.106 24.195)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="ayb1dwuvg"/><stop offset=".937" class="z6xoafb2r"/></radialGradient><radialGradient id="i2zysTc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1394 1.4599 -1.43346 -2.10066 28.718 21.514)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="iwzcNhy" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .49204 .64628 28.086 21.352)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="iZ63QxM" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.3 12.076)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="i23qVDd" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.842 15.2)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="iAVESGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.912 16.559)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="i5xVnnM" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.506 16.95)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="in9D37C" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.98 20.82)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="iXVKjoe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12692 -1.56257 1.8364 -1.3244 16.412 19.941)" gradientUnits="userSpaceOnUse"><stop class="c41784n4d"/><stop offset="1" class="r5_3rkp5l"/></radialGradient><radialGradient id="itnqXmw" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.5843 -1.90116 0 15.15 18.43)" gradientUnits="userSpaceOnUse"><stop class="nj4ic69jx"/><stop offset="1" class="nf6el5bab"/></radialGradient><radialGradient id="iSc5sSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 26.073 23.36)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iLgkWPt" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 26.073 24.778)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iTpjkAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 26.073 26.148)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="i2C6icf" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 26.073 27.63)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ijRE5Rc" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 .38 20.907)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="izzacne" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.04 13.773)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iBFYhud" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 17.905 12.342)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="ioqe5PF" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.686 8.623)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="ihCGABd" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.6809 -10.5013 0 15.657 6.17)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="o7t4t3b1f"/><stop offset=".98" class="i2fp2bjvp"/></radialGradient><radialGradient id="iVutCPQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 17.545 11.029)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="i3NKwHb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.956 -.884)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="i3qmljd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49598 .5363 -1.37 -21.703 18.53 13.33)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iWqBnzc" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 8.306 9.609)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iaa28gT" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 6.03 14.109)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iLwUPGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.6732 0 12.882 11.846)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="i8vglTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 15.564 13.702)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="irfHK1d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69206 .7501 -1.20547 -2.71927 15.68 13.133)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iG4JCub" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.193 9.532)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iPA5XNd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9117 6.52447 -8.23836 -3.67657 14.666 6.743)" gradientUnits="userSpaceOnUse"><stop class="jy25td8rp"/><stop offset="1" class="xftsofb3t"/></radialGradient><radialGradient id="isQeZnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29688 1.23651 0 13.133 11.212)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="hkf1_jbsj"/><stop offset="1" class="wrhkd7bsy"/></radialGradient><radialGradient id="ibsBrib" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 14.606 15.965)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i1vZIBc" cx="0" cy="0" r="1" gradientTransform="matrix(2.7406 -7.14959 10.14519 3.88889 9.39 10.417)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="ik4JgPe" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 14.548 -3.014)scale(6.72756 9.54634)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iqI2Pjb" cx="0" cy="0" r="1" gradientTransform="rotate(-115.408 11.119 -2.698)scale(2.63838 3.11466)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="i8AaFsc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 15.351 5.15)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iNpvKsd" cx="0" cy="0" r="1" gradientTransform="matrix(3.2182 -5.09542 5.6452 3.56544 9.667 9.093)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="icFzY4c" cx="0" cy="0" r="1" gradientTransform="matrix(3.5152 -2.83003 4.38594 5.4478 17.016 7.706)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="iNo0Ygf" cx="0" cy="0" r="1" gradientTransform="matrix(2.95886 -2.64821 4.8482 5.41692 17.731 8.964)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="iyuiK3d" cx="0" cy="0" r="1" gradientTransform="matrix(3.22527 .72413 -.30318 1.35036 16.868 7.143)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iBhxRfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.28 11.425)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i2hrT5Q" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.344 1.58)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2YbMqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 12.915 11.425)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ieJstKJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 12.629 11.644)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ioR5Gmc" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 19.715 11.44)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iHhovZb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.076 11.984)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iIFQPxc" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.19 12.156)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="i85wCKc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 10.182 12.08)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iEfdNae" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 10.183 12.082)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><linearGradient id="iJRf5ve" x1="16.901" x2="15.504" y1="26.125" y2="25.823" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="iUWyfvy" x1="7.199" x2="6.027" y1="25.925" y2="25.925" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="i6s8fUc" x1="23.128" x2="23.77" y1="26.011" y2="25.979" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iZ5WhAd" x1="22.77" x2="18.395" y1="15.996" y2="28.506" gradientUnits="userSpaceOnUse"><stop class="qm8srpk6b"/><stop offset="1" class="knnk86b5x"/></linearGradient><linearGradient id="i79PCzd" x1="16.824" x2="17.431" y1="26.496" y2="26.56" gradientUnits="userSpaceOnUse"><stop class="o_frn_b6l"/><stop offset="1" class="ohgvqyqas"/></linearGradient><linearGradient id="iVTNAFd" x1="20.787" x2="20.787" y1="15.996" y2="16.818" gradientUnits="userSpaceOnUse"><stop offset=".165" class="oy7fe6bjb"/><stop offset="1" class="ivc982b0q"/></linearGradient><linearGradient id="iZEqgFe" x1="7.895" x2="11.895" y1="17.636" y2="28.886" gradientUnits="userSpaceOnUse"><stop class="e55i1-bjj"/><stop offset="1" class="rqyrdfbps"/></linearGradient><linearGradient id="iiPCr1U" x1="8.35" x2="9.063" y1="15.249" y2="19.306" gradientUnits="userSpaceOnUse"><stop class="agyv0c9kf"/><stop offset="1" class="vxg8xmb_d"/></linearGradient><linearGradient id="iX0ccme" x1="7.895" x2="8.309" y1="22.573" y2="22.37" gradientUnits="userSpaceOnUse"><stop class="maqiohbml"/><stop offset="1" class="qndc1xila"/></linearGradient><linearGradient id="iQmngve" x1="23.395" x2="21.614" y1="26.042" y2="26.042" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="i1mwDmb" x1="8.114" x2="10.395" y1="27.854" y2="26.698" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="iXnq14c" x1="15.111" x2="15.111" y1="17.396" y2="28.5" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iaifHBY" x1="17.886" x2="15.925" y1="22.085" y2="21.757" gradientUnits="userSpaceOnUse"><stop offset=".196" class="xco_-7b_j"/><stop offset=".671" class="ru3ag_b2y"/></linearGradient><linearGradient id="icZB7gd" x1="25.739" x2="25.739" y1="15.692" y2="19.748" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="iPOWwZb" x1="25.933" x2="25.792" y1="16.628" y2="17.831" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="ieqPEld" x1="23.236" x2="23.363" y1="16.564" y2="17.001" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="iv0nzLc" x1="26.936" x2="24.648" y1="21.135" y2="21.135" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="idIxI5c" x1="24.466" x2="24.847" y1="20.977" y2="20.949" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="izXqsfd" x1="27.084" x2="26.822" y1="20.849" y2="20.825" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="i1OyRuf" x1="27.996" x2="23.128" y1="26.382" y2="26.382" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="ijtpuMe" x1="23.742" x2="25.663" y1="24.179" y2="24.179" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i3iTTLc" x1="23.742" x2="25.663" y1="25.621" y2="25.621" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ijoyhQe" x1="23.742" x2="25.663" y1="27.051" y2="27.051" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i7EbdYh" x1="20.255" x2="17.726" y1="14.027" y2="14.027" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iLSrYId" x1="15.936" x2="15.097" y1="13.016" y2="13.051" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="ivCDNXd" x1="15.097" x2="15.097" y1="14.156" y2="13.691" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iPyKhId" x1="15.097" x2="15.097" y1="11.45" y2="11.997" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="iNr0Xge" x1="15.513" x2="15.513" y1="14.293" y2="14.101" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="i3DWtSd" x1="13.896" x2="14.214" y1="15.727" y2="14.892" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="ihbmcue" x1="21.95" x2="10.337" y1="6.679" y2="6.679" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="itry7kc" x1="18.058" x2="17.744" y1="11.479" y2="11.673" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iT614la" x1="13.659" x2="13.345" y1="11.479" y2="11.673" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBawrDe" x1="21.534" x2="20.327" y1="11.506" y2="13.682" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="ipczPke" x1="9.248" x2="10.706" y1="12.21" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="isIdhye" x1="20.551" x2="20.551" y1="11.197" y2="12.955" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><filter id="id3V7ib" width="5.513" height="4.74" x="12.848" y="23.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2318"/></filter><filter id="iE65LUT" width="6.102" height="1.228" x="22.791" y="16.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2318"/></filter><filter id="iCuMYSc" width="1.075" height="1.075" x="25.198" y="20.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2318"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2318" result="effect2_innerShadow_4002_2318"/></filter><filter id="ijodwZb" width="5.967" height="5.967" x="12.166" y="14.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".125"/></filter><filter id="ikbW4Yd" width="5.813" height="5.813" x="12.243" y="14.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".25"/></filter><filter id="iN5BQLc" width="5.369" height="6.076" x="23.128" y="22.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2318"/></filter><filter id="iNLZ08c" width="2.319" height=".3" x="23.592" y="23.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".05"/></filter><filter id="iy8xRbe" width="2.319" height=".3" x="23.592" y="25.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".05"/></filter><filter id="iMqneUd" width="2.319" height=".3" x="23.592" y="26.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".05"/></filter><filter id="iTZsqUr" width="11.22" height="12.442" x="10.034" y="6.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2318"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2318" result="effect2_innerShadow_4002_2318"/></filter><filter id="ithrQNb" width="3.747" height="4.9" x="13.082" y="10.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".5"/></filter><filter id="i5JwX9c" width="2.277" height="3.3" x="13.959" y="11.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".1"/></filter><filter id="iHn27bc" width="3.718" height="1.573" x="13.238" y="14.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".05"/></filter><filter id="iPJsEld" width="12.873" height="8.357" x="8.661" y="2.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2318"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2318" result="effect2_innerShadow_4002_2318"/></filter><filter id="iLPEZit" width="2.339" height="1.19" x="16.687" y="8.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2318"/></filter><filter id="iAWw0Kd" width="2.339" height="1.176" x="11.43" y="8.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2318"/></filter><filter id="iJ4nmEe" width="6.584" height="5.992" x="9.017" y="4.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2318"/><feGaussianBlur result="effect2_foregroundBlur_4002_2318" stdDeviation=".125"/></filter><filter id="imsr8Bb" width="7.112" height="5.986" x="14.938" y="4.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2318"/><feGaussianBlur result="effect2_foregroundBlur_4002_2318" stdDeviation=".125"/></filter><filter id="ieyy4Cb" width=".787" height=".696" x="16.545" y="10.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".05"/></filter><filter id="iHmmY5q" width=".891" height=".913" x="17.385" y="11.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".1"/></filter><filter id="iHzC8Vb" width=".986" height="1.04" x="12.943" y="10.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".1"/></filter><filter id="iQFffmc" width=".913" height=".705" x="12.188" y="10.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".05"/></filter><filter id="iwa9FLb" width="1.329" height="2.379" x="9.017" y="10.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".125"/></filter><filter id="i6Xhrsc" width="1.806" height="2.758" x="19.648" y="10.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".25"/></filter><filter id="ivqX26K" width="2.405" height="1.16" x="11.349" y="8.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".125"/></filter><filter id="i4ATRPe" width="2.405" height="1.16" x="16.666" y="8.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".125"/></filter><filter id="iMgZLBe" width="5.367" height="3.046" x="16.113" y="4.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2318" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:singer-medium" /></template>
<style>
.a7vxm9bsf {
  fill: var(--svg-color--563936, #563936);
  d: path("m20.31 9.993l-.03-.631c-.01-.764-.64-1.394-1.404-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.521 4.154");
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.abxpw76-t {
  d: path("M13.729 11.736c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.agyv0c9kf {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.ayb1dwuvg {
  stop-color: var(--svg-color--704239, #704239);
  stop-opacity: 0;
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b6nw53xek {
  d: path("M10.012 11.143a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c1345jbbi {
  fill: var(--svg-color--725050, #725050);
  d: path("M19.496 6.729H17.36a.496.496 0 1 1 .08-.987c.554.088 1.29.211 1.783.334c1.115.276 1.423.819 1.509 1.206a1.55 1.55 0 0 0-1.235-.553");
}

.c41784n4d {
  stop-color: var(--svg-color--ae8074, #AE8074);
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ci5sdgbnv {
  d: path("M17.216 11.137c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn088_52m {
  stop-color: var(--svg-color--b17f71, #B17F71);
}

.csxoxoo5l {
  d: path("M15.118 17.396c-1.16 0-2.3.17-3.38.49l1.1 5.87c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.czkqlgk-l {
  d: path("M19.953 5.699c.514.177.975.536 1.267 1.051a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.27.875v1.188a1.75 1.75 0 0 0-.668-.269l.079-1.606a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379l.031 1.537c-.254.038-.52.123-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.445a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.589-.188.912-.188c.843 0 1.58.456 1.989 1.132c.308.51.79.88 1.352 1.073");
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.djc5ph3fa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 26.973h2.02");
}

.e-coa4boh {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m14.715 11.627l-.531 1.838c-.109.378.152.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e55i1-bjj {
  stop-color: var(--svg-color--e86b1f, #E86B1F);
}

.efd79xblx {
  d: path("M19.959 13.592a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.019a4.1 4.1 0 0 0 .345-1.18z");
}

.ejynn6b3w {
  stop-color: var(--svg-color--ef5945, #EF5945);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fmhio103w {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.707 10.677c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.g_w780bgb {
  d: path("M20.148 12.955q.05-.879.094-1.758c.401.055.712.426.712.876c0 .484-.36.878-.806.882");
}

.g04s-nsls {
  cx: 15.149px;
  cy: 17.646px;
  r: 2.734px;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.h1qr0p-pz {
  d: path("m28.214 16.536l-4.844-.02a.57.57 0 0 0-.58.579c0 .324.255.578.58.578l4.844.02a.57.57 0 0 0 .578-.578a.585.585 0 0 0-.578-.58");
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hkf1_jbsj {
  stop-color: var(--svg-color--be2252, #BE2252);
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i03-jcbks {
  stop-color: var(--svg-color--d14708, #D14708);
}

.i2fp2bjvp {
  stop-color: var(--svg-color--965268, #965268);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.ivc982b0q {
  stop-color: var(--svg-color--e48043, #E48043);
  stop-opacity: 0;
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j2psesb3q {
  d: path("m14.715 11.627l-.531 1.838c-.109.378.152.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jmqc0ac7y {
  d: path("M23.128 28.496v-7.268l-3.52 7.267z");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jy25td8rp {
  stop-color: var(--svg-color--e82d86, #E82D86);
}

.jybffqyvj {
  cx: 15.149px;
  cy: 17.755px;
  r: 2.406px;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.ke6r5xbfo {
  d: path("M25.736 21.624a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .974");
}

.keegem7ly {
  d: path("M27.018 28.495c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.kfasd4a1w {
  d: path("M27.277 20.82c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.knnk86b5x {
  stop-color: var(--svg-color--d53939, #D53939);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l-omnpbuk {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.216 11.137c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.l4rg4-bid {
  stop-color: var(--svg-color--f6874a, #F6874A);
  stop-opacity: 0;
}

.l5l7f-yex {
  d: path("M18.077 11.723a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.l6cm_-bda {
  d: path("m15.33 6.726l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.804-.767-1.688c0-1.072.781-1.613 1.28-1.959c.14-.098.259-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.893v1.485z");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.lnw18-bme {
  d: path("M15.118 16.308c-1.16 0-2.487.21-3.567.58l1.29 6.873c.72.325 1.497.434 2.317.434c.77 0 1.51-.073 2.19-.351l1.313-6.956c-1.05-.383-2.384-.58-3.544-.58");
}

.lys-m0b9d {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m14.696 11.823l-.59 1.838c-.102.378.14.756.484.756h.731c.344 0 .586-.384.485-.756l-.495-1.838c-.106-.408-.504-.408-.615 0");
}

.m27qtcbgg {
  stop-color: var(--svg-color--d14708, #D14708);
  stop-opacity: 0;
}

.m5ccv-bud {
  d: path("M17.282 10.949a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.m71o8sbbb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 24.101h2.02");
}

.maqiohbml {
  stop-color: var(--svg-color--ec7046, #EC7046);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbqhfeswf {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.696 9.477c-.257-.184-.898-.509-1.655-.381");
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mnp72frot {
  stop-color: var(--svg-color--f6874a, #F6874A);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.mxt8fccfn {
  d: path("M12.848 23.755v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.n7v132bzw {
  d: path("M24.313 16.509h-5.58l-2.274 11.997h3.149l5.325-11.017a.685.685 0 0 0-.62-.98");
}

.nf6el5bab {
  stop-color: var(--svg-color--a06665, #A06665);
}

.nj4ic69jx {
  stop-color: var(--svg-color--975567, #975567);
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nnbtyr9mx {
  d: path("M15.103 6.328a.66.66 0 0 0-.402-.137h-1.273q-.277 0-.541.044l-2.249 6.619h1.81l-.508 2.687l3.687-5.132h-1.883z");
}

.nuwn-flsy {
  d: path("M10.053 10.478a1.62 1.62 0 0 0-1.392 1.598c0 .86.673 1.56 1.521 1.607a78 78 0 0 1-.129-3.205");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.nym90gb4n {
  stop-color: var(--svg-color--7a4845, #7A4845);
}

.o_frn_b6l {
  stop-color: var(--svg-color--cc2820, #CC2820);
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o7t4t3b1f {
  stop-color: var(--svg-color--ad777d, #AD777D);
  stop-opacity: 0;
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.obn84gbyd {
  fill: var(--svg-color--000, #000);
  d: path("M16.77 11.84a.51.51 0 0 1 .512-.51a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ohgvqyqas {
  stop-color: var(--svg-color--cc2820, #CC2820);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oy7fe6bjb {
  stop-color: var(--svg-color--e48043, #E48043);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.pqv2eiavf {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M11.687 9.253a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qhd9kobac {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.488 10.677c.654 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.341h-2.232a.23.23 0 0 1-.227-.272c.126-.64.69-1.127 1.371-1.127");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qm8srpk6b {
  stop-color: var(--svg-color--f98026, #F98026);
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qndc1xila {
  stop-color: var(--svg-color--ec7046, #EC7046);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.r5_3rkp5l {
  stop-color: var(--svg-color--ae8074, #AE8074);
  stop-opacity: 0;
}

.rbv2mhb1n {
  d: path("M7.078 28.495v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.rkgfshb2k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 25.543h2.02");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rokcf0btl {
  d: path("M10.236 13.592a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.rqyrdfbps {
  stop-color: var(--svg-color--e22f38, #E22F38);
}

.ru3ag_b2y {
  stop-color: var(--svg-color--ac7b6e, #AC7B6E);
  stop-opacity: 0;
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.rzqjthgas {
  stop-color: var(--svg-color--ef5945, #EF5945);
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.u3pl8_5vo {
  cx: 12.644px;
  cy: 11.33px;
  rx: 0.39px;
  ry: 0.197px;
}

.u6064t8zh {
  d: path("M10.273 15.107a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.117-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.116 3.691.239 5.557");
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.urb_bmb5c {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.747 14.843h-.001a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.646.88c.69 0 1.297-.352 1.645-.88a.214.214 0 0 0-.023-.272a.23.23 0 0 0-.271-.045c-.39.204-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.usejpb1rc {
  d: path("M15.098 15.238c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846c.664 0 1.248-.339 1.583-.846c.086-.13-.061-.279-.198-.21a3 3 0 0 1-1.386.33");
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uzyno4b9g {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M18.83 9.362a1.85 1.85 0 0 0-.687-.412c-.304-.095-.686-.121-1.213-.057a.277.277 0 1 0 .068.551c.48-.059.776-.028.978.036c.198.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v4t_cwbem {
  d: path("M25.726 26.335a.784.784 0 0 1-.782-.71l-.67-6.428l2.975.01l-.731 6.428a.8.8 0 0 1-.792.7");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vktvlibck {
  fill: var(--svg-color--533634, #533634);
  d: path("m15.33 6.726l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.804-.767-1.688c0-1.072.781-1.613 1.28-1.959c.14-.098.259-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.893v1.485z");
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vxg8xmb_d {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
  stop-opacity: 0;
}

.vzfrs2boh {
  d: path("M12.914 10.948a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w0st2glnz {
  d: path("M25.766 19.694a2.498 2.498 0 1 0 0-4.996a2.498 2.498 0 0 0 0 4.996");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wrhkd7bsy {
  stop-color: var(--svg-color--be2252, #BE2252);
  stop-opacity: 0;
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.x-k68jb_j {
  d: path("m20.31 9.993l-.03-.631c-.01-.764-.64-1.394-1.404-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.521 4.154");
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xco_-7b_j {
  stop-color: var(--svg-color--814c4b, #814C4B);
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xftsofb3t {
  stop-color: var(--svg-color--d42552, #D42552);
}

.xjfgv-bnu {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.848 23.755v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yfvv7-pgl {
  d: path("M5.405 16.517h6.086l2.248 11.989h-2.79l-5.88-11.529c-.086-.125-.07-.46.336-.46");
}

.yw8aqm-as {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.724 9.533c.257-.185.898-.51 1.656-.382");
}

.z3s-bsbfl {
  fill: var(--svg-color--000, #000);
  d: path("M13.425 11.84a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.z6xoafb2r {
  stop-color: var(--svg-color--704239, #704239);
}

.z9s_-ergi {
  cx: 12.644px;
  cy: 11.33px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.za-e59biz {
  d: path("M20.02 13.683c.065-1.065.129-2.128.184-3.192a1.61 1.61 0 0 1-.185 3.191");
}

.zdbcebemm {
  d: path("M7.078 28.496h3.87L7.078 20.9z");
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

.zx87c8buv {
  d: path("M23.128 23.382a.81.81 0 0 1 .816-.802h3.054c.745 0 1.349.589 1.349 1.315v3.515c0 .605-.503 1.096-1.124 1.096h-3.28a.81.81 0 0 1-.816-.803c0-.314.187-.588.458-.72a.8.8 0 0 1-.457-.72c0-.314.186-.589.457-.72a.8.8 0 0 1-.457-.72a.8.8 0 0 1 .457-.72a.8.8 0 0 1-.457-.72");
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
