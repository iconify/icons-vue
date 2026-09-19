<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#istHwtW)"><path fill="url(#i3coWuc)" class="bscxqsbmf"/><path fill="url(#ixjLcsc)" class="bscxqsbmf"/><path fill="url(#iwAClXq)" class="bscxqsbmf"/><path fill="url(#iDjhZFe)" class="bscxqsbmf"/><path fill="url(#isvD3we)" class="bscxqsbmf"/></g><path fill="url(#igtPXve)" class="m1i1rlbvk"/><g filter="url(#ibE5REo)"><path class="xk18tyb3e"/></g><path class="m3se_ob2r"/><path fill="url(#i4RHwye)" class="zqss5obsp"/><path fill="url(#i86fP2c)" class="zqss5obsp"/><path fill="url(#i23ntQe)" class="zqss5obsp"/><path class="jse2phbtg"/><path fill="url(#i2nIhZb)" class="om0oq7b1v"/><path fill="url(#ivP9Jjb)" class="om0oq7b1v"/><path fill="url(#i77Ytid)" class="om0oq7b1v"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#iTdOGsd)" class="vqc4qgzhu"/><path fill="url(#iJIw8ya)" class="vqc4qgzhu"/><path fill="url(#i1AZebc)" class="dvr2s59yl"/><path fill="url(#iX9JgNb)" class="dvr2s59yl"/><path fill="url(#idlbkMe)" class="rom2yrbwh"/><path fill="url(#iIvEVud)" class="rom2yrbwh"/><path fill="url(#iXRw9pd)" class="rom2yrbwh"/><path fill="url(#iz9xh1o)" class="rom2yrbwh"/><path fill="url(#i6G3R0c)" class="rom2yrbwh"/><g filter="url(#iUse2Dd)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#i6UWpmd)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#i92lDPb)"><path fill="url(#iu9cByc)" class="d2s-wtuyq"/></g><g filter="url(#iAufXHf)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#ixaGDYd)" class="u1e8ikbzb"/></g><g filter="url(#igCY1Gh)"><path class="z5g21op2e"/></g><g filter="url(#i6kLUis)"><path fill="url(#ifKU5mc)" class="pv8cx5b7o"/><path fill="url(#iSwnSae)" class="pv8cx5b7o"/><path fill="url(#iWwBHGd)" class="pv8cx5b7o"/><path fill="url(#iviU92d)" class="pv8cx5b7o"/><path fill="url(#iJJBG7d)" class="pv8cx5b7o"/></g><g filter="url(#i8cDEAe)"><path stroke="url(#iBO8D2b)" class="cjq4b16bn"/></g><g filter="url(#i3ljege)"><path stroke="url(#ijHs0Pe)" class="luyfkt2yj"/></g><g filter="url(#iUNXTPc)"><path stroke="url(#i9Ji0Wc)" class="eqaszhbhb"/></g><g filter="url(#iTD89wc)"><path fill="url(#ia0VMee)" class="z7mjnzo7z"/><path fill="url(#iSivVbe)" class="z7mjnzo7z"/></g><g filter="url(#i6r46xc)"><path fill="url(#iGkaf6c)" class="sgnusbbpk"/></g><g filter="url(#iGa6eqc)"><path class="efim5dbsq"/><path fill="url(#ip8IP5F)" class="no06f5auh"/></g><g filter="url(#i6MP3ac)"><path class="hopwcurle"/><path fill="url(#if1fkPb)" class="oysohxb1f"/></g><g filter="url(#ip8K4Hb)"><path fill="url(#ip1u6zb)" class="whl2tibnh"/><path fill="url(#iXXrbhe)" class="whl2tibnh"/><path fill="url(#iXySGEb)" class="whl2tibnh"/><path fill="url(#iv2dXmq)" class="whl2tibnh"/><path fill="url(#iLicQje)" class="whl2tibnh"/><path fill="url(#iGjkhsd)" class="whl2tibnh"/><path fill="url(#iaYguuc)" class="whl2tibnh"/><path fill="url(#iDnUyqI)" class="whl2tibnh"/></g><path fill="url(#iBdiPbe)" class="whl2tibnh"/><path fill="url(#iRJyf5c)" class="whl2tibnh"/><g filter="url(#is0BPgD)"><path class="ovr34kb4r"/></g><g filter="url(#iBmsKEb)"><path class="gbyxjxbro"/><path fill="url(#iriWrbe)" class="ul_jtlbud"/><path fill="url(#iGF8xKe)" class="ul_jtlbud"/><path fill="url(#i2ZoFNe)" class="ul_jtlbud"/><path fill="url(#iZznTKe)" class="ul_jtlbud"/><path fill="url(#iy5m6Xd)" class="ul_jtlbud"/></g><path stroke="url(#ihMBgse)" class="t1ugmprxk"/><g filter="url(#iXdxNIc)"><path class="xiachsq4a"/></g><g filter="url(#ieVwulv)"><path class="ucrjblgwm"/></g><g filter="url(#itsUGDc)"><path class="tb8881clk"/></g><g filter="url(#ia3FWWi)"><path class="ghi_lsnyn"/></g><path class="atbjq1b8w"/><path fill="url(#iFp4iUc)" class="lne1m6bxy"/><path class="rhrcxjbmm"/><g filter="url(#iLyDHzF)"><path class="oxgphmv9v"/><path fill="url(#i68Oj5b)" class="xnm_x0bwx"/></g><g filter="url(#iOiOlTd)"><path fill="url(#iHQuopc)" class="c9yxjvbit"/></g><path class="ir1x0nx0c"/><path fill="url(#ip9Aqwe)" class="ukimnksrq"/><path class="iu3fbm0ve"/><g filter="url(#imP7CRd)"><path fill="url(#i4T8Mvd)" class="hz7n1lbjz"/></g><g filter="url(#iYPHnCV)"><ellipse transform="rotate(-27.914 13.252 9.992)" class="t8k3swbbh"/><ellipse fill="url(#i0kd1Ed)" transform="rotate(-27.914 13.252 9.992)" class="wil3xbozx"/></g><g filter="url(#iljQqzZ)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#impYsLc)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><defs><radialGradient id="ixjLcsc" cx="0" cy="0" r="1" gradientTransform="rotate(140.889 3.842 5.316)scale(4.24611 1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="k2gc6wbep"/><stop offset="1" class="l764hibce"/></radialGradient><radialGradient id="iwAClXq" cx="0" cy="0" r="1" gradientTransform="matrix(2.11985 0 0 3.47579 20.212 7.694)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="w9txrw6kc"/><stop offset="1" class="h-4ghpb7u"/></radialGradient><radialGradient id="iDjhZFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90841 -5.85233 0 14.758 12.65)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="dc6jrkblm"/><stop offset="1" class="oy6n6fbyn"/></radialGradient><radialGradient id="isvD3we" cx="0" cy="0" r="1" gradientTransform="rotate(117.05 7.869 13.544)scale(2.23819 1.04512)" gradientUnits="userSpaceOnUse"><stop class="o2so46b0g"/><stop offset="1" class="m92umxb0w"/></radialGradient><radialGradient id="i23ntQe" cx="0" cy="0" r="1" gradientTransform="rotate(135.74 4.223 11.079)scale(3.58199 4.84976)" gradientUnits="userSpaceOnUse"><stop class="qunsngokg"/><stop offset="1" class="zsyglhsdv"/></radialGradient><radialGradient id="i77Ytid" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="f7vxzf2re"/><stop offset="1" class="bjz-35bmd"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="i1AZebc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99943 1.36453 -1.33986 -1.96328 27.592 23.749)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="iX9JgNb" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 27.001 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="i6G3R0c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.553 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="iu9cByc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.875 -3.15122 0 15.915 16.444)" gradientUnits="userSpaceOnUse"><stop class="lmaptxboi"/><stop offset="1" class="xi21cobts"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="ixaGDYd" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.839)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="iSwnSae" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.364 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iWwBHGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.364 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iviU92d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.364 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iJJBG7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.364 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ia0VMee" cx="0" cy="0" r="1" gradientTransform="rotate(-43.767 24.286 -20.623)scale(1.62195 2.626)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iSivVbe" cx="0" cy="0" r="1" gradientTransform="matrix(.56791 0 0 .51526 21.44 8.942)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="ip8IP5F" cx="0" cy="0" r="1" gradientTransform="matrix(-.40745 0 0 -.9238 10.362 10.63)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="if1fkPb" cx="0" cy="0" r="1" gradientTransform="matrix(.66527 -.09951 .15385 1.02855 20.948 10.726)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="ip1u6zb" cx="0" cy="0" r="1" gradientTransform="rotate(155.407 8.263 7.037)scale(7.36936 9.81575)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iXXrbhe" cx="0" cy="0" r="1" gradientTransform="rotate(156.406 7.76 7.293)scale(2.45132 1.69842)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iXySGEb" cx="0" cy="0" r="1" gradientTransform="matrix(1.32825 -4.01732 5.12803 1.69549 13.531 16.653)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iv2dXmq" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.5407 -11.8314 0 15.918 10.506)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="i-e9u7b7b"/><stop offset="1" class="jipe58b1s"/></radialGradient><radialGradient id="iLicQje" cx="0" cy="0" r="1" gradientTransform="rotate(168.978 8.244 6.734)scale(7.24885 12.394)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iGjkhsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17683 1.45515 0 18.13 9.57)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iaYguuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34224 1.54986 0 13.62 9.336)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iDnUyqI" cx="0" cy="0" r="1" gradientTransform="rotate(105.2 5.84 10.17)scale(3.41944 2.75387)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iBdiPbe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32427 0 0 -6.59153 21.009 11.091)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iRJyf5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.43533 -9.18006 0 15.759 7.37)" gradientUnits="userSpaceOnUse"><stop class="e0gv9o0se"/><stop offset="1" class="ov73ftb4r"/></radialGradient><radialGradient id="iriWrbe" cx="0" cy="0" r="1" gradientTransform="rotate(-101.645 13.104 -.756)scale(2.25681 .64762)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iZznTKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.23563 16.25 12.154)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iFp4iUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.887 10.088)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i68Oj5b" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.32 .762)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ip9Aqwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.523 10.088)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i0kd1Ed" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.237 10.307)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><filter id="istHwtW" width="15.95" height="13.5" x="7.71" y="4.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.101961 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.313726 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1954" result="effect2_innerShadow_4002_1954"/></filter><filter id="ibE5REo" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".5"/></filter><filter id="iUse2Dd" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1954"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1954" result="shape"/></filter><filter id="i6UWpmd" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><filter id="i92lDPb" width="4.352" height="2.789" x="13.564" y="15.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.439216 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><filter id="iAufXHf" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><filter id="igCY1Gh" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".325"/></filter><filter id="i6kLUis" width="4.468" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><filter id="i8cDEAe" width="2.097" height=".3" x="23.353" y="25.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".05"/></filter><filter id="i3ljege" width="2.097" height=".3" x="23.275" y="27.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".05"/></filter><filter id="iUNXTPc" width="2.097" height=".3" x="23.353" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".05"/></filter><filter id="iTD89wc" width="1.514" height="3.441" x="20.627" y="8.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><filter id="i6r46xc" width="1.671" height="3.2" x="9.269" y="9.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><filter id="iGa6eqc" width="1.529" height="2.579" x="9.572" y="9.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".175"/></filter><filter id="i6MP3ac" width="1.947" height="2.903" x="20.167" y="9.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".25"/></filter><filter id="ip8K4Hb" width="10.5" height="11.373" x="10.509" y="5.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><filter id="is0BPgD" width="2.877" height="3.9" x="14.059" y="9.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".25"/></filter><filter id="iBmsKEb" width="2.377" height="3.4" x="14.516" y="9.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".125"/></filter><filter id="iXdxNIc" width="2.439" height="1.19" x="17.294" y="7.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><filter id="ieVwulv" width="2.439" height="1.176" x="12.038" y="7.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><filter id="itsUGDc" width="2.611" height="1.227" x="16.995" y="9.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><filter id="ia3FWWi" width="2.611" height="1.227" x="11.806" y="9.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><filter id="iLyDHzF" width=".787" height=".696" x="17.153" y="9.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".05"/></filter><filter id="iOiOlTd" width=".891" height=".913" x="17.993" y="9.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".1"/></filter><filter id="imP7CRd" width=".986" height="1.04" x="13.55" y="9.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".1"/></filter><filter id="iYPHnCV" width=".913" height=".705" x="12.795" y="9.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1954" stdDeviation=".05"/></filter><filter id="iljQqzZ" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><filter id="impYsLc" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1954"/></filter><linearGradient id="i3coWuc" x1="22.414" x2="14.931" y1="6.466" y2="18.664" gradientUnits="userSpaceOnUse"><stop class="xsvwa8b4m"/><stop offset=".862" class="j07mou_8a"/></linearGradient><linearGradient id="igtPXve" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="hzctbo64o"/><stop offset="1" class="ncpoyrbpw"/></linearGradient><linearGradient id="i4RHwye" x1="14.633" x2="13.974" y1="19.957" y2="19.239" gradientUnits="userSpaceOnUse"><stop class="ptx8-dg4d"/><stop offset="1" class="m1cydckkt"/></linearGradient><linearGradient id="i86fP2c" x1="11.699" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="zsyglhsdv"/></linearGradient><linearGradient id="i2nIhZb" x1="19.937" x2="18.312" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="z9cu3vbra"/><stop offset="1" class="ul2cu2h0c"/></linearGradient><linearGradient id="ivP9Jjb" x1="17" x2="17.937" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="iTdOGsd" x1="23.473" x2="23.473" y1="29.781" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="ifKU5mc" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="iBO8D2b" x1="23.503" x2="25.212" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ijHs0Pe" x1="23.425" x2="25.134" y1="27.375" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i9Ji0Wc" x1="23.503" x2="25.212" y1="28.68" y2="28.68" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iGkaf6c" x1="9.269" x2="10.789" y1="10.716" y2="10.716" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="iGF8xKe" x1="14.766" x2="15.705" y1="12.004" y2="12.004" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="i2ZoFNe" x1="15.705" x2="15.705" y1="12.769" y2="12.091" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iy5m6Xd" x1="15.705" x2="15.705" y1="9.869" y2="11.319" gradientUnits="userSpaceOnUse"><stop class="q8865acps"/><stop offset="1" class="hntnb_b7m"/></linearGradient><linearGradient id="ihMBgse" x1="14.668" x2="15.103" y1="14.384" y2="13.696" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iHQuopc" x1="18.665" x2="18.351" y1="10.142" y2="10.335" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4T8Mvd" x1="14.267" x2="13.953" y1="10.142" y2="10.335" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-mechanic-medium" /></template>
<style>
.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.atbjq1b8w {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.096 9.339c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.bjz-35bmd {
  stop-color: var(--svg-color--d6cbdf, #D6CBDF);
  stop-opacity: 0;
}

.bscxqsbmf {
  d: path("M23.51 10.724c0-1.722-2.299-2.453-2.299-3.474l-.14-.68c0-.92.252-1.39-.103-2.011H10.65c-.306.62-.394 1.784-.394 2.704v.01c0 1.048-2.247 1.352-2.247 3.45c0 .541.118 1.041.335 1.502c.069.15.069.33 0 .48a3.4 3.4 0 0 0-.335 1.481c0 1.862 1.488 3.373 3.32 3.373h8.86c1.832 0 3.32-1.511 3.32-3.373c0-.53-.118-1.03-.335-1.48a.58.58 0 0 1 0-.481c.217-.46.335-.971.335-1.501");
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.c9yxjvbit {
  d: path("M18.684 10.386a.84.84 0 0 0-.232-.463l-.26.285l.118.229z");
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.cjq4b16bn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 25.992H25.3");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d2s-wtuyq {
  d: path("M15.717 18.637c-1.523-.508-1.95-1.488-2.153-2.59h4.352c-.367 2.017-1.68 2.488-2.199 2.59");
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.dc6jrkblm {
  stop-color: var(--svg-color--160c19, #160C19);
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0gv9o0se {
  stop-color: var(--svg-color--6e485f, #6E485F);
}

.efim5dbsq {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M10.668 9.69a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.eqaszhbhb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 28.602H25.3");
}

.f7vxzf2re {
  stop-color: var(--svg-color--8e7f98, #8E7F98);
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.ft5dv1b6b {
  fill: none;
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.gbyxjxbro {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.323 10.174l-.532 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.ghamttb0q {
  stop-color: var(--svg-color--99959a, #99959A);
}

.ghi_lsnyn {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M13.199 9.274c.765.039 1.099.422 1.218.613l-2.011.461c-.141.008-.485-.086-.563-.246a.31.31 0 0 1 .05-.363c.177-.203.675-.497 1.306-.465");
}

.gmjyv1b7b {
  stop-color: var(--svg-color--aba1bb, #ABA1BB);
  stop-opacity: 0;
}

.gvyr5190s {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
  stop-opacity: 0;
}

.h-4ghpb7u {
  stop-color: var(--svg-color--150a0d, #150A0D);
  stop-opacity: 0;
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
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

.hntnb_b7m {
  stop-color: var(--svg-color--a27672, #A27672);
  stop-opacity: 0;
}

.hopwcurle {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.667 11.579q.057-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.hz7n1lbjz {
  d: path("M14.336 10.398c0-.288-.234-.48-.298-.538l-.288.279l.177.36z");
}

.hzctbo64o {
  stop-color: var(--svg-color--d6c6ed, #D6C6ED);
}

.i-e9u7b7b {
  stop-color: var(--svg-color--9d6578, #9D6578);
  stop-opacity: 0;
}

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.ir1x0nx0c {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.314 9.339c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.iu3fbm0ve {
  fill: var(--svg-color--000, #000);
  d: path("M14.032 10.503a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .061-.236");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j07mou_8a {
  stop-color: var(--svg-color--23121c, #23121C);
}

.jipe58b1s {
  stop-color: var(--svg-color--a65f88, #A65F88);
}

.jse2phbtg {
  fill: var(--svg-color--f4e6ff, #F4E6FF);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k2gc6wbep {
  stop-color: var(--svg-color--5c4a46, #5C4A46);
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l764hibce {
  stop-color: var(--svg-color--5c4a46, #5C4A46);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmaptxboi {
  stop-color: var(--svg-color--ac727e, #AC727E);
}

.lne1m6bxy {
  d: path("M17.889 9.61a.892.892 0 0 1 .86 1.129h-1.724a.896.896 0 0 1 .864-1.128");
}

.luyfkt2yj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.425 27.297h1.797");
}

.lwc2zdrqr {
  d: path("M13.155 24.45c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29zm0-.5h-1.45c-.99 0-1.79.8-1.79 1.79s.8 1.79 1.79 1.79h1.45c.99 0 1.79-.8 1.79-1.79s-.8-1.79-1.79-1.79");
}

.m1cydckkt {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
  stop-opacity: 0;
}

.m1i1rlbvk {
  d: path("M15.745 15.5c-6.07 0-11 4.92-11 11V30h21.08l.91-3.5c0-6.08-4.92-11-10.99-11");
}

.m3se_ob2r {
  fill: var(--svg-color--eddffd, #EDDFFD);
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.m92umxb0w {
  stop-color: var(--svg-color--534341, #534341);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.ncpoyrbpw {
  stop-color: var(--svg-color--cdb2d2, #CDB2D2);
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.no06f5auh {
  d: path("M10.668 9.69a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.o2so46b0g {
  stop-color: var(--svg-color--534341, #534341);
}

.o2y-twbma {
  stop-color: var(--svg-color--2780b8, #2780B8);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o7pw9mb8f {
  stop-color: var(--svg-color--f03a62, #F03A62);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh9185bnq {
  stop-color: var(--svg-color--2860c0, #2860C0);
  stop-opacity: 0;
}

.oj6on8fvq {
  stop-color: var(--svg-color--847596, #847596);
  stop-opacity: 0;
}

.om0oq7b1v {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.ov73ftb4r {
  stop-color: var(--svg-color--6e485f, #6E485F);
  stop-opacity: 0;
}

.ovr34kb4r {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.219 10.37l-.635 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.383.52-.756l-.531-1.838c-.114-.407-.542-.407-.661 0");
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.oxgphmv9v {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.823 9.8c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.136.388-.05");
}

.oy6n6fbyn {
  stop-color: var(--svg-color--160c19, #160C19);
  stop-opacity: 0;
}

.oysohxb1f {
  d: path("M20.667 11.579q.057-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.ptx8-dg4d {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
}

.pv8cx5b7o {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.q8865acps {
  stop-color: var(--svg-color--a27672, #A27672);
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qunsngokg {
  stop-color: var(--svg-color--7c6987, #7C6987);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0l64jbzx {
  stop-color: var(--svg-color--b7a9c2, #B7A9C2);
}

.rhrcxjbmm {
  fill: var(--svg-color--000, #000);
  d: path("M17.378 10.503c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.236");
}

.rom2yrbwh {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.101-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.s2-xryl0i {
  d: path("M12.045 6.26c-.68.31-1.29.74-1.89 1.31l.41.51c.31.38.85.49 1.28.25c.76-.42 2.11-.99 3.9-.99s3.14.57 3.9.99a1 1 0 0 0 1.27-.25l.41-.51c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0");
}

.s8-qpgb5g {
  stop-color: var(--svg-color--3b71d9, #3B71D9);
}

.sf2388bnl {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
}

.sgnusbbpk {
  d: path("M10.65 9.03a1.61 1.61 0 0 0 .14 3.2a78 78 0 0 1-.14-3.2");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t1ugmprxk {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.343 13.412c.393.205.862.323 1.362.323a2.94 2.94 0 0 0 1.362-.323a.2.2 0 0 1 .242.04c.057.06.078.155.02.241m-2.986-.28l2.945.253m-2.945-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.254m3.208.027l-.042-.027m.042.027l-.042-.027m.042.027a1.94 1.94 0 0 1-1.625.869c-.682 0-1.28-.347-1.625-.868m3.208-.028a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.583-.846m-.042.028l.042-.028m-.042.028l.042-.028");
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.t8k3swbbh {
  cx: 13.252px;
  cy: 9.992px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tb8881clk {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M18.214 9.274c-.766.039-1.1.422-1.22.613l2.012.461c.141.008.485-.086.563-.246a.31.31 0 0 0-.05-.363c-.177-.203-.675-.497-1.305-.465");
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.ucrjblgwm {
  fill: var(--svg-color--432a28, #432A28);
  d: path("M12.294 8.057a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.uhp0yeb2h {
  stop-color: var(--svg-color--c6b9db, #C6B9DB);
}

.ukimnksrq {
  d: path("M13.52 9.61a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.ul_jtlbud {
  d: path("m15.323 10.174l-.532 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.ul2cu2h0c {
  stop-color: var(--svg-color--f0e1ff, #F0E1FF);
  stop-opacity: 0;
}

.unsdl8pjp {
  stop-color: var(--svg-color--9b80b4, #9B80B4);
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vqc4qgzhu {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.402-1.54-6.44-3.96-8.457");
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9txrw6kc {
  stop-color: var(--svg-color--150a0d, #150A0D);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.whl2tibnh {
  d: path("M19.795 7.306H16.48c-1.314 0-2.509-.594-3.245-1.656a.272.272 0 0 0-.478.048l-.08.195a2.34 2.34 0 0 1-1.233 1.238a.4.4 0 0 1-.11.049c-.249.117-.816.487-.826 1.452l.14 3.235c.119 2.866 2.378 4.786 5.115 4.786s4.996-1.92 5.116-4.786l.129-3.08c-.02-1.354-1.025-1.48-1.214-1.48");
}

.wil3xbozx {
  cx: 13.252px;
  cy: 9.992px;
  rx: 0.39px;
  ry: 0.197px;
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xi21cobts {
  stop-color: var(--svg-color--b9887f, #B9887F);
}

.xiachsq4a {
  fill: var(--svg-color--432a28, #432A28);
  d: path("M19.438 8.173a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.121-1.212-.057a.277.277 0 1 0 .067.55c.481-.058.776-.028.979.036c.198.062.332.164.49.3a.277.277 0 1 0 .364-.418");
}

.xk18tyb3e {
  fill: var(--svg-color--caadc8, #CAADC8);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.xnm_x0bwx {
  d: path("M17.823 9.8c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.136.388-.05");
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xsvwa8b4m {
  stop-color: var(--svg-color--513637, #513637);
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5g21op2e {
  fill: var(--svg-color--b3a4c6, #B3A4C6);
  d: path("M24.755 21.651h.78v3.662h-.78z");
}

.z7mjnzo7z {
  d: path("M20.627 12.23q.1-1.597.184-3.192a1.61 1.61 0 0 1-.184 3.191");
}

.z8optlbcz {
  stop-color: var(--svg-color--9680b0, #9680B0);
}

.z9cu3vbra {
  stop-color: var(--svg-color--fff7ff, #FFF7FF);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zqss5obsp {
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.zsyglhsdv {
  stop-color: var(--svg-color--eee0fe, #EEE0FE);
  stop-opacity: 0;
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

</style>
