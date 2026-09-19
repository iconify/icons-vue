<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iSmlKAb)"><path fill="url(#iqnjV7p)" clip-rule="evenodd" class="khwpi-bjf"/><path fill="url(#iVUAN5d)" clip-rule="evenodd" class="khwpi-bjf"/><path fill="url(#izvIPce)" clip-rule="evenodd" class="khwpi-bjf"/><path fill="url(#ioQwh8c)" clip-rule="evenodd" class="khwpi-bjf"/><path fill="url(#i0k0Cad)" clip-rule="evenodd" class="khwpi-bjf"/><path fill="url(#iMfibGd)" clip-rule="evenodd" class="khwpi-bjf"/><path fill="url(#ixmslxd)" clip-rule="evenodd" class="khwpi-bjf"/><path fill="url(#iOckrLb)" clip-rule="evenodd" class="khwpi-bjf"/><path fill="url(#iwvOqxd)" clip-rule="evenodd" class="khwpi-bjf"/><path fill="url(#iHhqmjb)" clip-rule="evenodd" class="khwpi-bjf"/><path fill="url(#ihU0jje)" clip-rule="evenodd" class="khwpi-bjf"/><path fill="url(#iYiEvjO)" clip-rule="evenodd" class="khwpi-bjf"/></g><path class="g__oa5l3d"/><path fill="url(#iSPdzGd)" class="l1b_ykqwm"/><path fill="url(#iMqaFxd)" class="l1b_ykqwm"/><path fill="url(#iOLQ0Ae)" class="e8rp0plon"/><path fill="url(#iiygEWb)" class="e8rp0plon"/><path fill="url(#iMWOxWd)" class="e8rp0plon"/><path fill="url(#iu0Uajb)" class="e8rp0plon"/><path fill="url(#ippXI7T)" class="e8rp0plon"/><path fill="url(#iPvGJPd)" class="e8rp0plon"/><g filter="url(#iZtcm8d)"><path class="y0fyr11lr"/></g><path fill="url(#i1GUEsb)" class="oqcyx-pxj"/><path fill="url(#if8wUFd)" class="oqcyx-pxj"/><path fill="url(#iZGIwkb)" class="oqcyx-pxj"/><path fill="url(#ikWuuse)" class="gpc4yrb7i"/><path fill="url(#iocagAM)" class="gpc4yrb7i"/><path fill="url(#i9dwJbe)" class="gxwpur07r"/><path fill="url(#imXPORd)" class="gxwpur07r"/><g filter="url(#iRgpfsv)"><path stroke="url(#iQpIg5d)" class="fnn_de3je"/></g><path fill="url(#iSKr12j)" class="lhlel5olk"/><path fill="url(#iumF7fe)" class="lhlel5olk"/><path fill="url(#iHXsJgc)" class="lhlel5olk"/><path fill="url(#i6uk8Cb)" class="lhlel5olk"/><path fill="url(#iCtAWGe)" class="lhlel5olk"/><path fill="url(#iirDFZc)" class="tt-edofyn"/><path fill="url(#igkTTDe)" class="tt-edofyn"/><path fill="url(#iJX92de)" class="tt-edofyn"/><path fill="url(#iFKYQxb)" class="sm9tqmbjd"/><path fill="url(#iQOksyC)" class="sm9tqmbjd"/><g filter="url(#iGS6OJI)"><path fill="url(#i9QAGrc)" class="i4iijtb6t"/><path fill="url(#i9QAGrc)" class="ubca08giz"/><path fill="url(#i9QAGrc)" class="w1el8fpbw"/></g><g filter="url(#iMwQNcc)"><path stroke="url(#is5EBGe)" class="u58--qoqs"/></g><g filter="url(#iujfWoc)"><path fill="url(#ikrkKre)" class="i2j1efb6w"/></g><path fill="url(#iBUQpCd)" class="i2j1efb6w"/><g filter="url(#iZRUD3Q)"><path fill="url(#iBWSAIc)" class="ourkj8bkm"/><path fill="url(#it6U0sd)" class="ourkj8bkm"/></g><g filter="url(#it7LAFe)"><path class="fx7dahbjy"/><path fill="url(#i8z9Rwd)" class="lg05s6bmi"/></g><g filter="url(#iSRT0xe)"><path class="e99oklb2m"/><path fill="url(#i1V1ESa)" class="khoy_rb6r"/></g><g filter="url(#i0Jv6Bd)"><path fill="url(#iSfv14Y)" class="fzh88fb3k"/><path fill="url(#iSXrLKb)" class="fzh88fb3k"/><path fill="url(#iXqnRAb)" class="fzh88fb3k"/><path fill="url(#iaI0RuX)" class="fzh88fb3k"/><path fill="url(#iFNFjae)" class="fzh88fb3k"/><path fill="url(#iyfVHgX)" class="fzh88fb3k"/><path fill="url(#iVJVxsd)" class="fzh88fb3k"/><path fill="url(#iYN26Oe)" class="fzh88fb3k"/></g><path fill="url(#i0f3Dub)" class="fzh88fb3k"/><g filter="url(#iPIheib)"><path class="uo0-ghbbf"/></g><g filter="url(#il4gxEm)"><path class="plw0esb_v"/><path fill="url(#io5lVbc)" class="d4np36b-v"/><path fill="url(#inrAMFc)" class="d4np36b-v"/><path fill="url(#i47X9hc)" class="d4np36b-v"/><path fill="url(#iDDf7lb)" class="d4np36b-v"/></g><path fill="url(#iFYXbQe)" class="d4np36b-v"/><path fill="url(#iTqBuVb)" class="d4np36b-v"/><path stroke="url(#isGw4Qb)" class="iqv1csbwr"/><g filter="url(#izPGbDd)"><path class="cua6x2aox"/></g><g filter="url(#ixwEOdd)"><path class="yag6j7guy"/></g><g filter="url(#iCHM8ld)"><path class="ex-n-tbhu"/></g><g filter="url(#itYCVkD)"><path clip-rule="evenodd" class="qlq5whbms"/></g><path class="yaufhbcdf"/><path fill="url(#iKSgHze)" class="u755f1b6y"/><path class="rv5en3foq"/><g filter="url(#ia0TvJc)"><path class="g9cco2blh"/><path fill="url(#imHau6d)" class="c71pwpbng"/></g><g filter="url(#i9trEOM)"><path fill="url(#ikZkfse)" class="v7-68mehm"/></g><path class="y_1e30-nh"/><path fill="url(#ioc1nmb)" class="keo3idcrz"/><path class="rs7-fdo3c"/><g filter="url(#ivvLGsb)"><path fill="url(#ip1Weyd)" class="fd55txu_x"/></g><g filter="url(#iKtVEuc)"><ellipse transform="rotate(-27.914 13.81 10.221)" class="k39foib-l"/><ellipse fill="url(#izhOfxb)" transform="rotate(-27.914 13.81 10.221)" class="c_o5f0urd"/></g><g filter="url(#imlBOad)"><path class="tl609ngub"/></g><g filter="url(#iuoJmye)"><path class="e06j5kbno"/></g><g filter="url(#idwHSce)"><path class="jpmts7n-y"/><path fill="url(#iY0owPg)" class="ktipiox8u"/><path fill="url(#i2PMh0d)" class="ktipiox8u"/></g><g filter="url(#id33mkU)"><path class="cqr1pdiwk"/><path fill="url(#iy8U1od)" class="vnd_xxf4j"/><path fill="url(#i9oFTWh)" class="vnd_xxf4j"/></g><g filter="url(#irKleCb)"><path stroke="url(#iaBv8Sd)" class="tdewmx94s"/></g><g filter="url(#iAHYjDd)"><path class="cndazablv"/></g><g filter="url(#i7tTVDd)"><path fill="url(#i18iKEL)" class="tgltk6byz"/><path fill="url(#iu6zoec)" class="tgltk6byz"/></g><path fill="url(#iJVoxlb)" class="awf64etot"/><path fill="url(#iMx7uHd)" class="awf64etot"/><path fill="url(#iBTSjDT)" class="awf64etot"/><defs><radialGradient id="iVUAN5d" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 2.087 13.825)scale(4.8224 6.02416)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="izvIPce" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02317 2.03885 -2.67889 -3.97221 13.114 13.851)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="ioQwh8c" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.89 8.383)scale(2.25688 1.73297)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="i0k0Cad" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.35 7.83)scale(2.59538 1.82822)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iMfibGd" cx="0" cy="0" r="1" gradientTransform="matrix(1.44124 2.74187 -3.80614 2.00067 12.692 2.497)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="ixmslxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51145 1.51156 -2.11238 -2.11223 22.5 4.676)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iOckrLb" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.412 6.756)scale(2.01344 4.19888)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iwvOqxd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.973 8.274)scale(3.04359 3.87708)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iHhqmjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.94841 -2.7791 2.1981 -.75014 21.346 7.502)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="ihU0jje" cx="0" cy="0" r="1" gradientTransform="matrix(1.57703 .16542 -.26803 2.55524 9.943 10.017)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="iYiEvjO" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.601 -4.02)scale(3.9825 1.43736)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iSPdzGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.737 23.114)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="iMqaFxd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 9.143 21.458)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="iOLQ0Ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 16.443 21.349)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="iiygEWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.435 16.895)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="iMWOxWd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 16.018 15.552)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iu0Uajb" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.768 15.317)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="ippXI7T" cx="0" cy="0" r="1" gradientTransform="rotate(-80.136 21.1 2.745)scale(9.65407 14.837)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="iPvGJPd" cx="0" cy="0" r="1" gradientTransform="rotate(91.544 .347 14.336)scale(4.63875 7.3062)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="q8_1e9bvu"/><stop offset="1" class="bh-nd0_an"/></radialGradient><radialGradient id="i1GUEsb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 -1.42188 1.19716 -2.49957 17.739 18.22)" gradientUnits="userSpaceOnUse"><stop class="xoj0cjj5j"/><stop offset="1" class="gietximnj"/></radialGradient><radialGradient id="if8wUFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -2.06 0 16.421 16.985)" gradientUnits="userSpaceOnUse"><stop class="ktrl6_0jb"/><stop offset="1" class="ki0_-eiqi"/></radialGradient><radialGradient id="iZGIwkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5407 -4.26182 0 16.421 14.544)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="v71br5-3y"/><stop offset="1" class="eqeqhqb5o"/></radialGradient><radialGradient id="iocagAM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 25.01 11.668)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="i9dwJbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.268 12.04)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="imXPORd" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.93 12.43)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="iumF7fe" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.33 8.558)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iHXsJgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.768 13.106)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="iCtAWGe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.768 16.895)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="iirDFZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.44 29.995)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="igkTTDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.206 29.995)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iFKYQxb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.547 29.995)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iQOksyC" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.497 23.157)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iBUQpCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.68548 -1.26197 1.42998 -.77674 11.058 12.635)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="iBWSAIc" cx="0" cy="0" r="1" gradientTransform="matrix(2.61006 -1.1864 1.44853 3.18675 20.62 11.408)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="it6U0sd" cx="0" cy="0" r="1" gradientTransform="matrix(1.26548 0 0 .54486 21.568 9.158)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="i8z9Rwd" cx="0" cy="0" r="1" gradientTransform="matrix(1.5833 -.11777 .09207 1.2377 20.988 11.065)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="i1V1ESa" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.78 5.474)scale(1.1073)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iSfv14Y" cx="0" cy="0" r="1" gradientTransform="matrix(-6.81974 3.14481 -4.20928 -9.12812 19.381 10.384)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iSXrLKb" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 8.039 7.58)scale(2.49783 1.73945)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iXqnRAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.35182 -4.11934 5.22667 1.7152 14.116 17.208)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iaI0RuX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.22581 7.48437 -9.35537 -1.53225 17.456 9.947)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="xrc8p-bjh"/><stop offset="1" class="h8jhbduob"/></radialGradient><radialGradient id="iFNFjae" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.548 6.988)scale(7.3795 12.7052)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iyfVHgX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.20671 1.48097 0 18.796 9.945)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iVJVxsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37632 1.57736 0 14.206 9.706)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iYN26Oe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91246 3.3836 -2.70744 -.73012 17.834 7.517)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="i0f3Dub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34776 0 0 -6.75892 21.726 11.505)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="io5lVbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.47769 -2.14337 .66057 -.14722 17.206 12.267)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iDDf7lb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8173 0 0 -.22849 16.954 12.49)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iTqBuVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.43787 .98715 -1.1864 -1.7281 16.779 11.865)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="iKSgHze" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85076 -1.35323 0 18.671 10.322)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="imHau6d" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.765 .691)scale(.39632 .54563)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ioc1nmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85076 -1.35323 0 14.095 10.322)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="izhOfxb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0081 -.51761 .62219 -.00974 13.794 10.551)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iY0owPg" cx="0" cy="0" r="1" gradientTransform="matrix(1.32338 -2.88938 1.47814 .677 10.45 8.098)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="i2PMh0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.20541 -2.07127 1.11199 .64714 12.24 7.07)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="iy8U1od" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21463 4.60494 -7.5288 -3.62078 18.387 2.638)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="i9oFTWh" cx="0" cy="0" r="1" gradientTransform="matrix(-.22056 1.43366 -3.08444 -.47453 16.604 3.025)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="i18iKEL" cx="0" cy="0" r="1" gradientTransform="matrix(-.6722 -3.65216 4.02251 -.74037 18.968 5.944)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="l382wkm5r"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="iu6zoec" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.02116 -7.18676 0 16.352 2.862)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="iMx7uHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.174 2.396)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="iBTSjDT" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.205 3.02)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><filter id="iSmlKAb" width="15.998" height="16.498" x="8.509" y="1.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1589"/></filter><filter id="iZtcm8d" width="5.32" height="9.565" x="13.761" y="9.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".2"/></filter><filter id="iRgpfsv" width=".65" height="8.268" x="24.546" y="3.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".125"/></filter><filter id="iGS6OJI" width="8.964" height="6.734" x="11.953" y="23.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".075"/></filter><filter id="iMwQNcc" width="1.172" height="2.394" x="13.087" y="3.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".125"/></filter><filter id="iujfWoc" width="3.525" height="3.375" x="9.782" y="9.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1589"/></filter><filter id="iZRUD3Q" width="3.375" height="3.625" x="19.758" y="9.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1589"/></filter><filter id="it7LAFe" width="3.253" height="3.252" x="19.819" y="9.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".25"/></filter><filter id="iSRT0xe" width="2.953" height="2.952" x="10.014" y="9.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".175"/></filter><filter id="i0Jv6Bd" width="10.686" height="11.506" x="11.04" y="5.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1589"/></filter><filter id="iPIheib" width="2.969" height="3.812" x="14.729" y="9.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".25"/></filter><filter id="il4gxEm" width="2.469" height="3.312" x="15.149" y="10.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".125"/></filter><filter id="izPGbDd" width="3.138" height="1.348" x="17.381" y="9.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1589"/></filter><filter id="ixwEOdd" width="3.138" height="1.348" x="12.248" y="9.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1589"/></filter><filter id="iCHM8ld" width="2.562" height="1.134" x="12.39" y="7.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1589"/></filter><filter id="itYCVkD" width="2.562" height="1.135" x="18.071" y="7.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1589"/></filter><filter id="ia0TvJc" width=".815" height=".72" x="17.906" y="9.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".05"/></filter><filter id="i9trEOM" width=".916" height=".939" x="18.792" y="9.949" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".1"/></filter><filter id="ivvLGsb" width="1.014" height="1.071" x="14.133" y="9.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".1"/></filter><filter id="iKtVEuc" width=".947" height=".729" x="13.337" y="9.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".05"/></filter><filter id="imlBOad" width="2.342" height=".996" x="18.117" y="8.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".1"/></filter><filter id="iuoJmye" width="2.342" height=".996" x="12.4" y="8.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".1"/></filter><filter id="idwHSce" width="4.478" height="4.794" x="9.739" y="3.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1589"/><feGaussianBlur result="effect2_foregroundBlur_4002_1589" stdDeviation=".2"/></filter><filter id="id33mkU" width="9.167" height="6.039" x="13.073" y="2.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1589"/><feGaussianBlur result="effect2_foregroundBlur_4002_1589" stdDeviation=".125"/></filter><filter id="irKleCb" width="1.171" height="2.393" x="13.051" y="3.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".1"/></filter><filter id="iAHYjDd" width="7.167" height="3.963" x="15.278" y="4.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1589" stdDeviation=".5"/></filter><filter id="i7tTVDd" width="12.363" height="3.035" x="10.201" y="3.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1589"/></filter><linearGradient id="iqnjV7p" x1="21.305" x2="14.872" y1="3.657" y2="14.941" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="ikWuuse" x1="24.125" x2="25.311" y1="8.942" y2="8.942" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="iQpIg5d" x1="25.371" x2="25.371" y1="3.708" y2="11.476" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="iSKr12j" x1="25.919" x2="23.6" y1="14.806" y2="14.806" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="i6uk8Cb" x1="23.719" x2="24.594" y1="14.485" y2="14.665" gradientUnits="userSpaceOnUse"><stop class="ud98q8dic"/><stop offset="1" class="yn026ikmt"/></linearGradient><linearGradient id="iJX92de" x1="9.35" x2="8.924" y1="28.064" y2="28.064" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="i9QAGrc" x1="16.435" x2="16.435" y1="29.864" y2="23.431" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="is5EBGe" x1="13.387" x2="13.959" y1="4.446" y2="5.783" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="ikrkKre" x1="9.782" x2="11.73" y1="11.039" y2="11.039" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="inrAMFc" x1="15.399" x2="16.383" y1="12.344" y2="12.344" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="i47X9hc" x1="16.383" x2="16.383" y1="13.085" y2="12.428" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iFYXbQe" x1="16.465" x2="16.465" y1="13.154" y2="13.008" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="isGw4Qb" x1="15.267" x2="15.751" y1="14.66" y2="13.913" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ikZkfse" x1="19.488" x2="19.158" y1="10.378" y2="10.581" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ip1Weyd" x1="14.875" x2="14.546" y1="10.378" y2="10.581" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaBv8Sd" x1="13.124" x2="13.637" y1="3.658" y2="4.984" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><linearGradient id="iJVoxlb" x1="18.205" x2="16.924" y1="3.958" y2="-.417" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-student-medium" /></template>
<style>
.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
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

.awf64etot {
  d: path("M24.378 3.605H8.408c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.bh-nd0_an {
  stop-color: var(--svg-color--1c0e20, #1C0E20);
  stop-opacity: 0;
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.c_o5f0urd {
  cx: 13.81px;
  cy: 10.221px;
  rx: 0.408px;
  ry: 0.207px;
}

.c71pwpbng {
  d: path("M18.604 10.02c.067.088-.072.197-.23.315c-.16.119-.277.202-.343.113c-.067-.09.008-.257.166-.376c.158-.118.34-.142.407-.053");
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clg68gimn {
  stop-color: var(--svg-color--f9b72a, #F9B72A);
}

.cndazablv {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m18.625 6.831l-1.494.275A.722.722 0 1 1 17 5.675h2.454c1.452 0 1.932 1.463 1.991 1.963a3.3 3.3 0 0 0-2.82-.807");
}

.codehtz3g {
  stop-color: var(--svg-color--db9820, #DB9820);
  stop-opacity: 0;
}

.cqr1pdiwk {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.75 2.778c-1.187-.262-2.254.923-2.377 1.362c1.103 3.718 3.894 3.514 6.649 3.208c1.649-.183 1.828.568 1.968.932c0-4.124-3.507-4.899-6.21-5.495z");
}

.cua6x2aox {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.58 10.351c.28-.49.702-.876 1.613-.876c.399 0 .783.11 1.125.387c.282.227.244.519.026.628l-.583.333c-.684-.22-1.44-.25-2.18-.472");
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.d4np36b-v {
  d: path("m15.982 10.57l-.557 1.782a.565.565 0 0 0 .546.733h.825c.386 0 .66-.372.545-.733l-.557-1.783c-.12-.395-.677-.395-.802 0");
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e06j5kbno {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.442 8.46c-.338-.082-1.18-.041-1.742.36");
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.e8o_wr2lc {
  stop-color: var(--svg-color--615b67, #615B67);
}

.e8rp0plon {
  d: path("M23.456 18.094a.24.24 0 0 0-.059-.29c-1.856-1.602-4.346-2.487-6.954-2.487s-5.113.894-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.614 7.03 4.614s5.73-2.014 7.013-4.614");
}

.e99oklb2m {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.49 12.074a1.126 1.126 0 1 0 0-2.253a1.126 1.126 0 0 0 0 2.253");
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.eqeqhqb5o {
  stop-color: var(--svg-color--5f4132, #5F4132);
}

.ex-n-tbhu {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m12.82 9.084l-.004.002a.281.281 0 0 1-.29-.482h.001l.001-.001l.003-.002l.01-.006a2 2 0 0 1 .156-.08c.103-.05.25-.113.43-.17a2.94 2.94 0 0 1 1.393-.114a.281.281 0 0 1-.098.553a2.4 2.4 0 0 0-1.124.097a3 3 0 0 0-.478.203");
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fd55txu_x {
  d: path("M14.947 10.647c0-.302-.245-.504-.312-.565l-.302.293l.186.378z");
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.fnn_de3je {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.871 3.709v7.767");
}

.ft5dv1b6b {
  fill: none;
}

.fx7dahbjy {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M21.445 12.074a1.126 1.126 0 1 0 0-2.253a1.126 1.126 0 0 0 0 2.253");
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.fzh88fb3k {
  d: path("M11.049 9.624h.013l-.011-.279l-.011-.32c.022-.996.602-1.38.85-1.51l.053-.02l.054-.022a2.42 2.42 0 0 0 1.248-1.295l.086-.203a.277.277 0 0 1 .483-.053a4.05 4.05 0 0 0 3.345 1.754h3.376c.19 0 1.135.092 1.191 1.397l-.124 3.223c-.13 2.939-2.424 4.912-5.226 4.912s-5.096-1.973-5.225-4.912z");
}

.g__oa5l3d {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.44 15.495c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.g_-uv52uc {
  stop-color: var(--svg-color--696070, #696070);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g9cco2blh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.604 10.02c.067.088-.072.197-.23.315c-.16.119-.277.202-.343.113c-.067-.09.008-.257.166-.376c.158-.118.34-.142.407-.053");
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gietximnj {
  stop-color: var(--svg-color--7e5059, #7E5059);
}

.gpc4yrb7i {
  d: path("M25.168 11.668V2.805h-.8v8.863z");
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gxwpur07r {
  d: path("M24.368 11.644a.838.838 0 1 0 .8 0z");
}

.h8jhbduob {
  stop-color: var(--svg-color--784856, #784856);
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

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.i2j1efb6w {
  d: path("M11.47 12.635a1.687 1.687 0 1 0 0-3.375a1.687 1.687 0 0 0 0 3.375");
}

.i4iijtb6t {
  d: path("M12.103 23.771c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iqv1csbwr {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.916 13.595c.424.226.93.356 1.467.356c.544 0 1.043-.13 1.467-.356a.21.21 0 0 1 .257.043c.06.064.082.166.022.258m-3.213-.301l3.17.274m-3.17-.274a.21.21 0 0 0-.257.045a.2.2 0 0 0-.021.257m.278-.302l-.236.274m3.449.027l-.042-.027m.042.027l-.042-.027m.042.027a2.076 2.076 0 0 1-3.491 0m3.449-.027a2.026 2.026 0 0 1-3.407 0m-.042.028l.042-.028m-.042.028l.042-.028");
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jpmts7n-y {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M11.068 4.668c.593-.628 1.716-.63 2.234-.535l.415 1.353c-.265-.041-.31-.002-.508.192c-.145 1.146-1.444 1.842-3.027 2.304c-.156-1.564.114-2.496.886-3.314");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k39foib-l {
  cx: 13.81px;
  cy: 10.221px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.408px;
  ry: 0.207px;
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.keo3idcrz {
  d: path("M14.093 9.821a.936.936 0 0 0-.902 1.183H15a1 1 0 0 0 .034-.247a.94.94 0 0 0-.94-.936");
}

.khoy_rb6r {
  d: path("M11.49 12.074a1.126 1.126 0 1 0 0-2.253a1.126 1.126 0 0 0 0 2.253");
}

.khwpi-bjf {
  fill-rule: evenodd;
  d: path("M23.918 12.426a3.46 3.46 0 0 0 .058-2.866h.005a3.3 3.3 0 0 0-.295-.537l-.002-.004a3.4 3.4 0 0 1-.552-1.857v-.01a3.46 3.46 0 0 0-3.46-3.46a.57.57 0 0 1-.477-.244a3.47 3.47 0 0 0-2.812-1.443a3.47 3.47 0 0 0-2.812 1.443a.6.6 0 0 1-.478.244l-.089.001a3.46 3.46 0 0 0-3.37 3.459v.01c0 .658-.191 1.306-.552 1.857l-.002.004a3.46 3.46 0 0 0-.231 3.403a.54.54 0 0 1 0 .477c-.213.446-.34.945-.34 1.476a3.37 3.37 0 0 0 3.375 3.374h8.999a3.37 3.37 0 0 0 3.374-3.374c0-.531-.127-1.03-.34-1.476a.54.54 0 0 1 0-.477M11.062 9.624h-.013l1.257 2.47c.129 2.938 1.276 0 4.077 0s4.023 3.27 4.152.332l1.191-3.353c-.056-1.305-1.002-1.397-1.19-1.397h-3.377a4.05 4.05 0 0 1-3.345-1.754a.277.277 0 0 0-.483.053l-.087.203a2.42 2.42 0 0 1-1.354 1.338c-.248.128-.828.513-.85 1.508l.01.321z");
}

.ki0_-eiqi {
  stop-color: var(--svg-color--804d60, #804D60);
  stop-opacity: 0;
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.ktipiox8u {
  d: path("M11.068 4.668c.593-.628 1.716-.63 2.234-.535l.415 1.353c-.265-.041-.31-.002-.508.192c-.145 1.146-1.444 1.842-3.027 2.304c-.156-1.564.114-2.496.886-3.314");
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.ktrl6_0jb {
  stop-color: var(--svg-color--804d60, #804D60);
}

.l1b_ykqwm {
  d: path("M16.44 15.495c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.l382wkm5r {
  stop-color: var(--svg-color--595260, #595260);
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lg05s6bmi {
  d: path("M21.445 12.074a1.126 1.126 0 1 0 0-2.253a1.126 1.126 0 0 0 0 2.253");
}

.lhlel5olk {
  d: path("m23.914 13.605l-.516 2.238a.45.45 0 0 0 .445.552h1.863a.45.45 0 0 0 .43-.557l-.542-2.24a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.oqcyx-pxj {
  d: path("M16.141 18.865c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587");
}

.ourkj8bkm {
  d: path("M21.445 12.635a1.687 1.687 0 1 0 0-3.375a1.687 1.687 0 0 0 0 3.375");
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.pk_j5sfiy {
  stop-color: var(--svg-color--33203c, #33203C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plw0esb_v {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.982 10.57l-.557 1.782a.565.565 0 0 0 .546.733h.825c.386 0 .66-.372.545-.733l-.557-1.783c-.12-.395-.677-.395-.802 0");
}

.pnxjkfbgy {
  stop-color: var(--svg-color--6a656f, #6A656F);
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q8_1e9bvu {
  stop-color: var(--svg-color--1c0e20, #1C0E20);
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qlq5whbms {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m20.296 8.604l-.144.241za.281.281 0 0 1-.288.482h-.001l-.005-.002a1 1 0 0 0-.118-.062a3 3 0 0 0-.36-.141a2.4 2.4 0 0 0-1.123-.097a.281.281 0 1 1-.098-.553a2.94 2.94 0 0 1 1.393.114a3.4 3.4 0 0 1 .585.25l.01.006l.003.002z");
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rs7-fdo3c {
  fill: var(--svg-color--000, #000);
  d: path("M14.628 10.757a.533.533 0 0 0-.536-.536a.533.533 0 0 0-.476.782h.948a.5.5 0 0 0 .064-.246");
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.rv5en3foq {
  fill: var(--svg-color--000, #000);
  d: path("M18.138 10.757c0-.298.237-.536.535-.536a.533.533 0 0 1 .476.782H18.2a.5.5 0 0 1-.064-.246");
}

.sm9tqmbjd {
  d: path("M23.665 29.995V18.21a10.97 10.97 0 0 1 3.765 8.286v3.5z");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tdewmx94s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.351 4.088c.025.255.246 1.213.572 1.793");
}

.tgltk6byz {
  d: path("m10.202 5.247l1.253-1.992l9.75-.11l1.36 2.063c-4.664 1.61-10.274.773-12.364.04");
}

.tl609ngub {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.417 8.46c.338-.082 1.18-.041 1.741.36");
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tt-edofyn {
  d: path("M9.206 29.995V18.21a10.97 10.97 0 0 0-3.766 8.286v3.5z");
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u58--qoqs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.387 4.085c.024.256.246 1.214.572 1.795");
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u755f1b6y {
  d: path("M18.674 9.821a.936.936 0 0 1 .901 1.183h-1.808a.94.94 0 0 1 .906-1.183");
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ubca08giz {
  d: path("M16.09 23.771c0-.188.154-.34.345-.34s.346.152.346.34v6.093h-.692z");
}

.ud98q8dic {
  stop-color: var(--svg-color--c57e10, #C57E10);
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.uo0-ghbbf {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.972 10.714l-.717 1.783a.565.565 0 0 0 .546.733h.824c.387 0 .66-.372.546-.733l-.557-1.783c-.12-.395-.517-.395-.642 0");
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v7-68mehm {
  d: path("M19.508 10.635a.9.9 0 0 0-.243-.486l-.273.3l.123.239z");
}

.v71br5-3y {
  stop-color: var(--svg-color--5f4132, #5F4132);
  stop-opacity: 0;
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vnd_xxf4j {
  d: path("M15.75 2.778c-1.187-.262-2.254.923-2.377 1.362c1.103 3.718 3.894 3.514 6.649 3.208c1.649-.183 1.828.568 1.968.932c0-4.124-3.507-4.899-6.21-5.495z");
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1el8fpbw {
  d: path("M20.076 23.771c0-.188.154-.34.345-.34s.346.152.346.34v6.093h-.691z");
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xoj0cjj5j {
  stop-color: var(--svg-color--976c65, #976C65);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xrc8p-bjh {
  stop-color: var(--svg-color--8b5766, #8B5766);
  stop-opacity: 0;
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.y_1e30-nh {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.876 9.537c-.685 0-1.263.472-1.42 1.11a.287.287 0 0 0 .28.357h2.34a.24.24 0 0 0 .238-.285a1.47 1.47 0 0 0-1.438-1.182");
}

.y0fyr11lr {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.141 18.865c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587Z");
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.yag6j7guy {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M15.186 10.351c-.279-.49-.702-.876-1.612-.876c-.4 0-.784.11-1.125.387c-.282.227-.245.519-.026.628l.583.333c.683-.22 1.44-.25 2.18-.472");
}

.yaufhbcdf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.89 9.537c.685 0 1.264.472 1.421 1.11a.287.287 0 0 1-.28.357h-2.34a.24.24 0 0 1-.238-.285a1.466 1.466 0 0 1 1.437-1.182");
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ym5q1xkkz {
  stop-color: var(--svg-color--372e41, #372E41);
}

.yn026ikmt {
  stop-color: var(--svg-color--df8f14, #DF8F14);
  stop-opacity: 0;
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

</style>
