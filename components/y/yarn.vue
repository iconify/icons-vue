<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="uhlvyfbfg"/><g filter="url(#itJ4Gcc)"><path class="uzr-obb6y"/></g><g filter="url(#iwejEHd)" class="ua4aa6b1e"><path class="a4js4nb4q"/><path stroke="url(#iEppE7c)" class="nu8ta1bsw"/><path stroke="url(#ivodT5D)" class="nu8ta1bsw"/></g><g filter="url(#i5zB0ab)"><path stroke="url(#iGhCFlb)" class="eku4hfcav"/></g><g filter="url(#is23vCf)"><path class="n6721tbre"/><path fill="url(#iN2MzyQ)" class="c1rhlybie"/><path fill="url(#idXmhqc)" class="c1rhlybie"/></g><path fill="url(#iqZXEZd)" class="c1rhlybie"/><g filter="url(#i5tpvZp)"><path class="x4pdwvb5l"/><path fill="url(#iG4K2Db)" class="xi7294xot"/><path fill="url(#id11vxe)" class="xi7294xot"/></g><path fill="url(#ik4tCwd)" class="xi7294xot"/><g filter="url(#ilywzJd)"><path fill="url(#i7xiMPc)" clip-rule="evenodd" class="bmmg3zb9d"/></g><g filter="url(#iiulamd)"><path fill="url(#iIrxvKe)" clip-rule="evenodd" class="u7g7udb4w"/></g><g filter="url(#itzaMAb)"><path class="r7tdhscjs"/><path fill="url(#i9Ji3de)" class="ajge1gw9w"/></g><g filter="url(#iynNpDd)"><path fill="url(#iutlRqV)" clip-rule="evenodd" class="ls1ll-5ml"/></g><path fill="url(#iOW89mk)" clip-rule="evenodd" class="ls1ll-5ml"/><g clip-rule="evenodd" filter="url(#iwUjJ5b)" class="d2kvgvbvc"><path fill="url(#i8BfTeo)" class="vbg8duboq"/><path fill="url(#iDjDmre)" class="vbg8duboq"/></g><g clip-rule="evenodd" filter="url(#ilJ1lFE)" class="d2kvgvbvc"><path fill="url(#iTNGbnc)" class="lzook0bqj"/><path fill="url(#iTvnEpe)" class="lzook0bqj"/></g><g clip-rule="evenodd" filter="url(#i7MD7Od)" class="d2kvgvbvc"><path fill="url(#irsw6Le)" class="fthdker4b"/><path fill="url(#iBoP7mc)" class="fthdker4b"/></g><path fill="url(#iViniud)" clip-rule="evenodd" class="uclsr6ztm"/><path fill="url(#iJ04yyd)" clip-rule="evenodd" class="uclsr6ztm"/><path fill="url(#iHeCFtb)" clip-rule="evenodd" class="uclsr6ztm"/><g filter="url(#idtkl9c)"><path fill="url(#ih5nxAd)" clip-rule="evenodd" class="al2inm8jw"/></g><g filter="url(#iT8Yabd)"><path fill="url(#iSzRZsd)" clip-rule="evenodd" class="ade8_ccbu"/></g><g filter="url(#i5dAqBc)"><path fill="url(#ix8KEdd)" class="cijtyccym"/></g><g filter="url(#iMsOyjq)"><path class="tnbpn7_9n"/></g><g filter="url(#icOJ94b)"><path class="lclvhvvqj"/><path fill="url(#iXlbbae)" class="gtf9ixt0n"/></g><path fill="url(#iMPSH2d)" class="hu-6_qber"/><path fill="url(#imIXVOe)" class="hu-6_qber"/><g filter="url(#idCcetb)"><path class="t5jhxhbsb"/></g><g filter="url(#iP5k4nd)"><path fill="url(#i6Snzle)" class="qv581m3yu"/><path fill="url(#iXbzOUc)" class="qv581m3yu"/></g><g filter="url(#indZQsc)"><path fill="url(#ixRDzJd)" class="oliqnpbhw"/><path fill="url(#iu1nU4c)" class="oliqnpbhw"/></g><g filter="url(#i9IyUgb)"><path fill="url(#iyzH7ye)" class="hw7vkobin"/><path fill="url(#iQdf4rP)" class="hw7vkobin"/></g><path class="lcawjkgqb"/><path fill="url(#iNG8FDy)" class="jig2hgcxc"/><path fill="url(#iOOq64c)" class="jig2hgcxc"/><path class="jirw25b0v"/><path fill="url(#iUAKxJb)" class="itdrkv56q"/><path fill="url(#iUfQ2Ad)" class="eq_gnubbz"/><path fill="url(#iEm4Vub)" class="eq_gnubbz"/><path fill="url(#imJzp6h)" class="eq_gnubbz"/><path fill="url(#iybkXQd)" class="lrj11tbwa"/><path fill="url(#iTm9wxb)" class="lrj11tbwa"/><path fill="url(#iRfvCZd)" class="wpy0gqbgd"/><path fill="url(#ighdn0d)" class="wpy0gqbgd"/><path fill="url(#iPRWPrm)" class="wpy0gqbgd"/><path class="g_srffb6i"/><path fill="url(#iDmlzqd)" class="oyay3xeql"/><path fill="url(#i3U157a)" class="oyay3xeql"/><path fill="url(#iYOZhic)" class="ygqz2qbix"/><path fill="url(#i5KRhWq)" class="ygqz2qbix"/><path fill="url(#iUoZokb)" class="ygqz2qbix"/><g clip-rule="evenodd" filter="url(#i1qH0Lb)" class="d2kvgvbvc"><path class="bi8he55nx"/><path fill="url(#iwRIWVd)" class="kxs0wub6r"/></g><defs><linearGradient id="iGhCFlb" x1="26.604" x2="13.354" y1="19.922" y2="28.578" gradientUnits="userSpaceOnUse"><stop class="o570a5brb"/><stop offset=".161" class="va-h0wb3n"/><stop offset=".438" class="va-h0wb3n"/><stop offset=".755" class="o570a5brb"/><stop offset="1" class="va-h0wb3n"/></linearGradient><linearGradient id="iN2MzyQ" x1="7.419" x2="6.887" y1="8.227" y2="9.062" gradientUnits="userSpaceOnUse"><stop class="kof_snpcv"/><stop offset="1" class="lps8dubve"/></linearGradient><linearGradient id="iG4K2Db" x1="11.76" x2="10.51" y1="4.953" y2="5.734" gradientUnits="userSpaceOnUse"><stop class="kof_snpcv"/><stop offset="1" class="lps8dubve"/></linearGradient><linearGradient id="i9Ji3de" x1="18.276" x2="18.159" y1="22.891" y2="23.156" gradientUnits="userSpaceOnUse"><stop class="kfxuneb5b"/><stop offset="1" class="u1xxm70nv"/></linearGradient><linearGradient id="iTNGbnc" x1="23.921" x2="18.543" y1="11.037" y2="14.473" gradientUnits="userSpaceOnUse"><stop class="uje_7zyns"/><stop offset="1" class="gyosz7bld"/></linearGradient><linearGradient id="irsw6Le" x1="24.921" x2="20.662" y1="13.766" y2="16.549" gradientUnits="userSpaceOnUse"><stop class="uje_7zyns"/><stop offset="1" class="gyosz7bld"/></linearGradient><linearGradient id="iJ04yyd" x1="23.542" x2="23.643" y1="17.945" y2="17.711" gradientUnits="userSpaceOnUse"><stop class="s8wnov83k"/><stop offset="1" class="etht2acik"/></linearGradient><linearGradient id="ih5nxAd" x1="15.706" x2="14.682" y1="21.188" y2="23.971" gradientUnits="userSpaceOnUse"><stop class="un4t0ebjn"/><stop offset="1" class="iajbjfsap"/></linearGradient><linearGradient id="iSzRZsd" x1="13.198" x2="11.635" y1="19.828" y2="23.078" gradientUnits="userSpaceOnUse"><stop class="wz_3h9bvx"/><stop offset="1" class="i6lcb04wb"/></linearGradient><linearGradient id="ix8KEdd" x1="10.211" x2="21.793" y1="11.879" y2="22.562" gradientUnits="userSpaceOnUse"><stop class="h2t5qtb0i"/><stop offset="1" class="mm42u-bci"/></linearGradient><linearGradient id="iXlbbae" x1="9.362" x2="9.28" y1="15.297" y2="15.238" gradientUnits="userSpaceOnUse"><stop class="xnvyu-bsh"/><stop offset="1" class="skdj8bb3a"/></linearGradient><linearGradient id="imIXVOe" x1="10.534" x2="10.12" y1="15.266" y2="15.531" gradientUnits="userSpaceOnUse"><stop offset=".346" class="a7hb4vb0g"/><stop offset="1" class="vppfm_o5v"/></linearGradient><linearGradient id="ixRDzJd" x1="14.76" x2="13.448" y1="20.391" y2="23.695" gradientUnits="userSpaceOnUse"><stop class="g_vitkkpg"/><stop offset="1" class="jo7lbebnm"/></linearGradient><linearGradient id="iu1nU4c" x1="14.635" x2="14.401" y1="20.211" y2="20.461" gradientUnits="userSpaceOnUse"><stop class="jtdfcccbu"/><stop offset="1" class="m6as_jbvu"/></linearGradient><linearGradient id="iyzH7ye" x1="16.854" x2="16.214" y1="22.141" y2="24.094" gradientUnits="userSpaceOnUse"><stop class="my79hoagd"/><stop offset="1" class="ui7zkqb3j"/></linearGradient><linearGradient id="iQdf4rP" x1="16.901" x2="16.749" y1="22.039" y2="22.281" gradientUnits="userSpaceOnUse"><stop class="pe_j6vf5l"/><stop offset="1" class="aqfmyjb3l"/></linearGradient><linearGradient id="iNG8FDy" x1="18.917" x2="18.788" y1="23.313" y2="23.537" gradientUnits="userSpaceOnUse"><stop class="y_uino-9f"/><stop offset="1" class="jaadwsmhc"/></linearGradient><linearGradient id="iOOq64c" x1="18.311" x2="18.448" y1="23.473" y2="23.545" gradientUnits="userSpaceOnUse"><stop class="cr028fb_q"/><stop offset="1" class="gk1qclksw"/></linearGradient><linearGradient id="iUAKxJb" x1="24.229" x2="24.346" y1="18.281" y2="18.07" gradientUnits="userSpaceOnUse"><stop class="boupukb2j"/><stop offset="1" class="gdr7i6_dc"/></linearGradient><linearGradient id="iUfQ2Ad" x1="25.035" x2="18.739" y1="12.327" y2="15.305" gradientUnits="userSpaceOnUse"><stop class="z3zh2tn7q"/><stop offset="1" class="qhyydagjr"/></linearGradient><linearGradient id="iEm4Vub" x1="19.042" x2="19.511" y1="15.453" y2="14.887" gradientUnits="userSpaceOnUse"><stop class="flj42achm"/><stop offset="1" class="jod_xkbfh"/></linearGradient><linearGradient id="iTm9wxb" x1="12.284" x2="12.081" y1="17.875" y2="18.047" gradientUnits="userSpaceOnUse"><stop class="s-jzrotas"/><stop offset="1" class="m_5it-7kr"/></linearGradient><linearGradient id="iRfvCZd" x1="23.615" x2="16.853" y1="9.988" y2="13.257" gradientUnits="userSpaceOnUse"><stop class="z3zh2tn7q"/><stop offset="1" class="qhyydagjr"/></linearGradient><linearGradient id="ighdn0d" x1="17.057" x2="17.62" y1="13.141" y2="12.688" gradientUnits="userSpaceOnUse"><stop class="flj42achm"/><stop offset="1" class="jod_xkbfh"/></linearGradient><linearGradient id="iDmlzqd" x1="15.449" x2="15.864" y1="10.652" y2="10.427" gradientUnits="userSpaceOnUse"><stop class="ecw09gbbw"/><stop offset="1" class="ypfuu3csx"/></linearGradient><linearGradient id="iYOZhic" x1="25.236" x2="20.933" y1="15.054" y2="16.905" gradientUnits="userSpaceOnUse"><stop class="z3zh2tn7q"/><stop offset="1" class="qhyydagjr"/></linearGradient><linearGradient id="i5KRhWq" x1="21.51" x2="21.872" y1="17.234" y2="16.666" gradientUnits="userSpaceOnUse"><stop class="flj42achm"/><stop offset="1" class="jod_xkbfh"/></linearGradient><radialGradient id="iEppE7c" cx="0" cy="0" r="1" gradientTransform="matrix(3.6875 6.0625 -7.49363 4.55797 24.417 17.453)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="b2j2gzqjn"/><stop offset="1" class="ifseox8je"/></radialGradient><radialGradient id="ivodT5D" cx="0" cy="0" r="1" gradientTransform="matrix(-.96875 0 0 -1.19743 19.51 29.031)" gradientUnits="userSpaceOnUse"><stop class="lqvaxzbux"/><stop offset="1" class="agfsiwbfu"/></radialGradient><radialGradient id="idXmhqc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.711 .09374 -.1411 -2.57532 10.41 11.039)" gradientUnits="userSpaceOnUse"><stop class="y9lyp-gal"/><stop offset="1" class="p7o9u2boj"/></radialGradient><radialGradient id="iqZXEZd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9885 -4.44242 1.69255 -2.2816 10.004 11.344)" gradientUnits="userSpaceOnUse"><stop offset=".944" class="e1ouw9rwx"/><stop offset="1" class="ff9ms9swx"/></radialGradient><radialGradient id="id11vxe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4297 -2.09374 .78912 -.53885 12.542 9.297)" gradientUnits="userSpaceOnUse"><stop class="y9lyp-gal"/><stop offset="1" class="p7o9u2boj"/></radialGradient><radialGradient id="ik4tCwd" cx="0" cy="0" r="1" gradientTransform="rotate(-113.349 9.101 .63)scale(7.7197 3.93414)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="e1ouw9rwx"/><stop offset="1" class="ff9ms9swx"/></radialGradient><radialGradient id="i7xiMPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29744 1.52449 -5.50119 -4.68188 20.485 15.777)" gradientUnits="userSpaceOnUse"><stop class="x0p1dibuj"/><stop offset="1" class="pyuxaqb6t"/></radialGradient><radialGradient id="iIrxvKe" cx="0" cy="0" r="1" gradientTransform="rotate(141.843 5.785 11.666)scale(1.66917 8.32595)" gradientUnits="userSpaceOnUse"><stop class="jf2x6tb3g"/><stop offset="1" class="uczevr53o"/></radialGradient><radialGradient id="iutlRqV" cx="0" cy="0" r="1" gradientTransform="rotate(-127.658 10.355 .216)scale(.76726 2.98907)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="d9rrtubtq"/><stop offset="1" class="hwofpxbtl"/></radialGradient><radialGradient id="iOW89mk" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 -.31055 2.73912 -1.65378 16.51 8.544)" gradientUnits="userSpaceOnUse"><stop class="fq4s_79vs"/><stop offset="1" class="pqaqosbst"/></radialGradient><radialGradient id="i8BfTeo" cx="0" cy="0" r="1" gradientTransform="matrix(-2.00517 1.4202 -1.09592 -1.5473 19.2 10.355)" gradientUnits="userSpaceOnUse"><stop class="f73gtebnn"/><stop offset="1" class="zs0d6g_8e"/></radialGradient><radialGradient id="iDjDmre" cx="0" cy="0" r="1" gradientTransform="matrix(.25077 .42725 -3.40113 1.99631 19.138 10.647)" gradientUnits="userSpaceOnUse"><stop class="k9h8gcbpc"/><stop offset="1" class="qccb9lb-j"/></radialGradient><radialGradient id="iTvnEpe" cx="0" cy="0" r="1" gradientTransform="matrix(4 -2.40625 .4895 .81372 18.51 13.797)" gradientUnits="userSpaceOnUse"><stop class="gs93f17of"/><stop offset="1" class="ozow_wafd"/></radialGradient><radialGradient id="iBoP7mc" cx="0" cy="0" r="1" gradientTransform="matrix(3.21072 -1.88779 .37986 .64606 20.578 15.93)" gradientUnits="userSpaceOnUse"><stop class="gs93f17of"/><stop offset="1" class="ozow_wafd"/></radialGradient><radialGradient id="iViniud" cx="0" cy="0" r="1" gradientTransform="matrix(0 .72505 -1.04883 0 23.88 17.377)" gradientUnits="userSpaceOnUse"><stop class="w6ahkvw3y"/><stop offset="1" class="kk-ipvbow"/></radialGradient><radialGradient id="iHeCFtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 -.96093 2.53695 -1.15503 24.198 18)" gradientUnits="userSpaceOnUse"><stop offset=".864" class="afopu6bub"/><stop offset="1" class="su9h7jbdx"/></radialGradient><radialGradient id="iMPSH2d" cx="0" cy="0" r="1" gradientTransform="rotate(120.769 .497 10.94)scale(3.14595 1.79919)" gradientUnits="userSpaceOnUse"><stop class="bsk_tybtc"/><stop offset="1" class="cctna7b1n"/></radialGradient><radialGradient id="i6Snzle" cx="0" cy="0" r="1" gradientTransform="rotate(137.626 6.287 10.709)scale(2.50261 7.70257)" gradientUnits="userSpaceOnUse"><stop class="cqty_yban"/><stop offset="1" class="waysqrx5t"/></radialGradient><radialGradient id="iXbzOUc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 5.965 13.146)scale(1.38832 5.79121)" gradientUnits="userSpaceOnUse"><stop class="eqprl0bpa"/><stop offset="1" class="s-our5bst"/></radialGradient><radialGradient id="imJzp6h" cx="0" cy="0" r="1" gradientTransform="rotate(-117.699 15.334 .651)scale(2.11769 7.30086)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="nd1bdjo5f"/><stop offset="1" class="txxm7ibdp"/></radialGradient><radialGradient id="iybkXQd" cx="0" cy="0" r="1" gradientTransform="rotate(123.69 1.468 12.293)scale(4.39427 2.89949)" gradientUnits="userSpaceOnUse"><stop class="nnq9uthin"/><stop offset="1" class="lae8hkb2v"/></radialGradient><radialGradient id="iPRWPrm" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 -2.5625 8.9446 -5.34496 20.573 12.703)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="nd1bdjo5f"/><stop offset="1" class="txxm7ibdp"/></radialGradient><radialGradient id="i3U157a" cx="0" cy="0" r="1" gradientTransform="matrix(.242 .34572 -3.39685 2.3778 18.198 9.77)" gradientUnits="userSpaceOnUse"><stop class="v1611ackt"/><stop offset="1" class="qse7avb0q"/></radialGradient><radialGradient id="iUoZokb" cx="0" cy="0" r="1" gradientTransform="rotate(-112.26 17.262 .686)scale(1.75931 5.73046)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="frheurbhh"/><stop offset="1" class="w3s_subrj"/></radialGradient><radialGradient id="iwRIWVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.96875 1.09374 -4.48706 -3.97428 17.135 20.39)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="bs7pjv-mv"/><stop offset="1" class="kt0d29boh"/></radialGradient><filter id="itJ4Gcc" width="1.552" height="1.072" x="14.322" y="7.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.403922 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="iwejEHd" width="14.243" height="11.847" x="13.349" y="18.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.317647 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="i5zB0ab" width="14.095" height="11.547" x="13.424" y="18.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4421" stdDeviation=".125"/></filter><filter id="is23vCf" width="6.645" height="5.189" x="4.016" y="6.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.486275 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="i5tpvZp" width="4.688" height="7.073" x="8.893" y="1.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.486275 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="ilywzJd" width="11.429" height="11.637" x="13.19" y="7.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.494118 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.203922 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4421" result="effect2_innerShadow_18_4421"/></filter><filter id="iiulamd" width="12.444" height="12.635" x="10.755" y="9.192" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.431373 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.203922 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4421" result="effect2_innerShadow_18_4421"/></filter><filter id="itzaMAb" width="1.501" height="1.4" x="17.117" y="22.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.211765 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="iynNpDd" width="3.349" height="2.04" x="14.625" y="7.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.25098 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="iwUjJ5b" width="5.601" height="3.632" x="16.019" y="8.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.419608 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="ilJ1lFE" width="5.984" height="3.771" x="17.89" y="10.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.309804 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="i7MD7Od" width="4.86" height="3.014" x="20.109" y="13.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.309804 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="idtkl9c" width="2.06" height="3.069" x="14.117" y="20.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.160784 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0823529 0 0 0 0 0.211765 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4421" result="effect2_innerShadow_18_4421"/></filter><filter id="iT8Yabd" width="2.465" height="3.929" x="11.316" y="18.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.121569 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.101961 0 0 0 0 0.270588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4421" result="effect2_innerShadow_18_4421"/></filter><filter id="i5dAqBc" width="12.946" height="13.116" x="9.383" y="10.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.439216 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="iMsOyjq" width=".914" height="1.604" x="8.354" y="13.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.345098 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="icOJ94b" width="1.592" height="2.788" x="8.203" y="13.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.129412 0 0 0 0 0.266667 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="idCcetb" width="2.551" height="3.937" x="9.169" y="16.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.305882 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.054902 0 0 0 0 0.192157 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4421" result="effect2_innerShadow_18_4421"/></filter><filter id="iP5k4nd" width="12.564" height="12.767" x="11.552" y="8.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.294118 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.580392 0 0 0 0 0.937255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4421" result="effect2_innerShadow_18_4421"/></filter><filter id="indZQsc" width="3.095" height="4.06" x="12.254" y="19.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.235294 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="i9IyUgb" width="2.59" height="2.5" x="15.146" y="21.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.235294 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/></filter><filter id="i1qH0Lb" width="11.776" height="12.074" x="8.741" y="11.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.317647 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4421"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0470588 0 0 0 0 0.203922 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4421" result="effect2_innerShadow_18_4421"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:yarn" /></template>
<style>
.a4js4nb4q {
  stroke: var(--svg-color--2481e6, #2481E6);
  d: path("M23.783 18.61c.833.166 2.678.921 3.203 2.796c.656 2.344-.812 4.578-2.89 4.578h-8.587a1.71 1.71 0 0 0-1.71 1.711v0a1.71 1.71 0 0 0 1.71 1.711h3.649");
}

.a7hb4vb0g {
  stop-color: var(--svg-color--1d498e, #1D498E);
}

.ade8_ccbu {
  fill-rule: evenodd;
  d: path("M13.651 19.453a.1.1 0 0 1 .016.122c-.459.796-1.007 1.859-1.325 3.007a.206.206 0 0 1-.315.116l-.536-.378a.29.29 0 0 1-.117-.304c.263-1.075.926-2.38 1.506-3.17a.098.098 0 0 1 .149-.012z");
}

.afopu6bub {
  stop-color: var(--svg-color--3281e4, #3281E4);
  stop-opacity: 0;
}

.agfsiwbfu {
  stop-color: var(--svg-color--4195f0, #4195F0);
  stop-opacity: 0;
}

.ajge1gw9w {
  d: path("M17.124 23.807c.159-.566.367-.938.503-1.121a.094.094 0 0 1 .123-.023l.693.4a.153.153 0 0 1 .054.21a3 3 0 0 0-.202.397a.53.53 0 0 1-.437.337l-.53.042a.193.193 0 0 1-.204-.242");
}

.al2inm8jw {
  fill-rule: evenodd;
  d: path("M16.038 21.501a.1.1 0 0 1 .026.13c-.43.744-.623 1.136-.89 2.064a.303.303 0 0 1-.357.213l-.416-.093a.297.297 0 0 1-.22-.377c.29-.943.572-1.634 1.012-2.44a.1.1 0 0 1 .148-.03z");
}

.aqfmyjb3l {
  stop-color: var(--svg-color--1b2aa6, #1B2AA6);
  stop-opacity: 0;
}

.b2j2gzqjn {
  stop-color: var(--svg-color--185cba, #185CBA);
}

.bi8he55nx {
  fill: var(--svg-color--1f51a1, #1F51A1);
  d: path("M9.337 11.839a.153.153 0 0 1 .278.006c1.414 3.252 4.914 8.216 10.815 11.071a.152.152 0 0 1 0 .275l-.724.34a.5.5 0 0 1-.436-.008c-5.807-2.982-9.113-7.847-10.358-10.588a.24.24 0 0 1 .003-.207z");
}

.bmmg3zb9d {
  fill-rule: evenodd;
  d: path("M13.98 7.873a.3.3 0 0 1 .389.17l.091.233c1.048 2.673 3.926 7.588 9.638 9.878l.232.093a.3.3 0 0 1 .167.39l-.186.464a.3.3 0 0 1-.39.167l-.232-.093c-6.075-2.36-9.18-7.658-10.287-10.485l-.091-.233a.3.3 0 0 1 .17-.389z");
}

.boupukb2j {
  stop-color: var(--svg-color--277fc2, #277FC2);
}

.bs7pjv-mv {
  stop-color: var(--svg-color--1848c3, #1848C3);
}

.bsk_tybtc {
  stop-color: var(--svg-color--2462b5, #2462B5);
}

.c1rhlybie {
  d: path("m4.413 8.18l5.24 3.351l.758-.93L5.4 6.77a.862.862 0 1 0-.988 1.41");
}

.cctna7b1n {
  stop-color: var(--svg-color--285cb1, #285CB1);
}

.cijtyccym {
  d: path("M20.92 22.932a.48.48 0 0 1-.443.011A23.1 23.1 0 0 1 9.576 11.788a.46.46 0 0 1 .026-.439a7 7 0 0 1 1.013-1.27c.099-.095.26-.055.312.073c2.081 5.147 6.242 9.495 11.34 11.569a.098.098 0 0 1 .035.157c-.425.454-.958.814-1.382 1.054");
}

.cqty_yban {
  stop-color: var(--svg-color--278be3, #278BE3);
}

.cr028fb_q {
  stop-color: var(--svg-color--111f87, #111F87);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d9rrtubtq {
  stop-color: var(--svg-color--0f72cc, #0F72CC);
}

.e1ouw9rwx {
  stop-color: var(--svg-color--c9ac91, #C9AC91);
  stop-opacity: 0;
}

.ecw09gbbw {
  stop-color: var(--svg-color--165794, #165794);
}

.eku4hfcav {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.783 18.61c.833.166 2.678.921 3.203 2.796c.656 2.344-.812 4.578-2.89 4.578h-8.587a1.71 1.71 0 0 0-1.71 1.711v0a1.71 1.71 0 0 0 1.71 1.711h3.649");
}

.eq_gnubbz {
  d: path("M23.683 11.649c-1.95.614-4.086 1.964-5.014 2.72a.143.143 0 0 0-.01.212c.357.36.933.862 1.288 1.164a.15.15 0 0 0 .196-.002c1.368-1.166 3.197-1.9 4.351-2.2a.15.15 0 0 0 .109-.177a6.5 6.5 0 0 0-.657-1.623a.225.225 0 0 0-.263-.095");
}

.eqprl0bpa {
  stop-color: var(--svg-color--3699ff, #3699FF);
}

.etht2acik {
  stop-color: var(--svg-color--1159a3, #1159A3);
  stop-opacity: 0;
}

.f73gtebnn {
  stop-color: var(--svg-color--187bdc, #187BDC);
}

.ff9ms9swx {
  stop-color: var(--svg-color--c9ac91, #C9AC91);
}

.flj42achm {
  stop-color: var(--svg-color--1a65aa, #1A65AA);
}

.fq4s_79vs {
  stop-color: var(--svg-color--1475d0, #1475D0);
}

.frheurbhh {
  stop-color: var(--svg-color--44b8ff, #44B8FF);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fthdker4b {
  d: path("M24.862 14.28a.307.307 0 0 1-.217.355c-1.775.52-3.144 1.425-3.637 1.806a.1.1 0 0 1-.122.002l-.716-.529a.147.147 0 0 1-.003-.236c.669-.5 2.287-1.592 4.228-2.12a.293.293 0 0 1 .362.225z");
}

.g_srffb6i {
  fill: var(--svg-color--2b9bf0, #2B9BF0);
  d: path("M18.124 7.643c-1.542.712-2.253 1.253-3.006 1.875a.15.15 0 0 0-.039.181c.203.398.548 1.017.816 1.446a.15.15 0 0 0 .22.036c1.301-1.043 3.194-2.099 4.313-2.552c.094-.038.124-.155.045-.22c-.515-.42-1.655-.675-2.197-.784a.25.25 0 0 0-.152.018");
}

.g_vitkkpg {
  stop-color: var(--svg-color--2356cf, #2356CF);
}

.gdr7i6_dc {
  stop-color: var(--svg-color--277fc2, #277FC2);
  stop-opacity: 0;
}

.gk1qclksw {
  stop-color: var(--svg-color--111f87, #111F87);
  stop-opacity: 0;
}

.gs93f17of {
  stop-color: var(--svg-color--317bde, #317BDE);
}

.gtf9ixt0n {
  d: path("M8.521 14.652c.292-.423.593-.814.743-1c.035.046.308.531.5.875a.25.25 0 0 1-.032.29a13 13 0 0 0-1.084 1.46c-.069.11-.274.068-.28-.063c-.016-.366-.02-.744-.01-1.07a.9.9 0 0 1 .163-.492");
}

.gyosz7bld {
  stop-color: var(--svg-color--0e5fb0, #0E5FB0);
}

.h2t5qtb0i {
  stop-color: var(--svg-color--266dc0, #266DC0);
}

.hu-6_qber {
  d: path("M8.466 16.536c.58-.973 1.2-1.672 1.435-1.927l1.02 1.627c.058.092.05.21-.019.296c-.615.77-1.293 1.94-1.656 2.604a.096.096 0 0 1-.168.006c-.446-.752-.634-1.792-.676-2.339a.45.45 0 0 1 .064-.267");
}

.hw7vkobin {
  d: path("M15.15 23.783a7.3 7.3 0 0 1 .873-2.133a.14.14 0 0 1 .2-.037l1.369.947a.103.103 0 0 1 .027.14a4 4 0 0 0-.52 1.248a.17.17 0 0 1-.17.14l-1.595-.07a.194.194 0 0 1-.184-.235");
}

.hwofpxbtl {
  stop-color: var(--svg-color--156fc3, #156FC3);
}

.i6lcb04wb {
  stop-color: var(--svg-color--1a3fb1, #1A3FB1);
}

.iajbjfsap {
  stop-color: var(--svg-color--1739b2, #1739B2);
}

.ifseox8je {
  stop-color: var(--svg-color--185cba, #185CBA);
  stop-opacity: 0;
}

.itdrkv56q {
  d: path("M24.549 17.819c-.246.063-.493.183-.581.279c.132.063.271.114.406.174c.084.037.188.021.227-.062a.6.6 0 0 0 .047-.331c-.007-.047-.053-.072-.1-.06");
}

.jaadwsmhc {
  stop-color: var(--svg-color--1e31bb, #1E31BB);
  stop-opacity: 0;
}

.jf2x6tb3g {
  stop-color: var(--svg-color--175dcf, #175DCF);
}

.jig2hgcxc {
  d: path("M18.255 23.73c.088-.191.19-.38.258-.505a.1.1 0 0 1 .136-.04l.519.28c.1.056.097.194-.011.236c-.24.092-.533.17-.759.215a.13.13 0 0 1-.143-.185");
}

.jirw25b0v {
  fill: var(--svg-color--35a4ff, #35A4FF);
  d: path("M24.549 17.819c-.246.063-.493.183-.581.279c.132.063.271.114.406.174c.084.037.188.021.227-.062a.6.6 0 0 0 .047-.331c-.007-.047-.053-.072-.1-.06");
}

.jo7lbebnm {
  stop-color: var(--svg-color--2449c9, #2449C9);
}

.jod_xkbfh {
  stop-color: var(--svg-color--1a65aa, #1A65AA);
  stop-opacity: 0;
}

.jtdfcccbu {
  stop-color: var(--svg-color--1a2e9c, #1A2E9C);
}

.k9h8gcbpc {
  stop-color: var(--svg-color--287ede, #287EDE);
}

.kfxuneb5b {
  stop-color: var(--svg-color--15259b, #15259B);
}

.kk-ipvbow {
  stop-color: var(--svg-color--1875e0, #1875E0);
}

.kof_snpcv {
  stop-color: var(--svg-color--ffbe6e, #FFBE6E);
}

.kt0d29boh {
  stop-color: var(--svg-color--1848c3, #1848C3);
  stop-opacity: 0;
}

.kxs0wub6r {
  d: path("M9.337 11.839a.153.153 0 0 1 .278.006c1.414 3.252 4.914 8.216 10.815 11.071a.152.152 0 0 1 0 .275l-.724.34a.5.5 0 0 1-.436-.008c-5.807-2.982-9.113-7.847-10.358-10.588a.24.24 0 0 1 .003-.207z");
}

.lae8hkb2v {
  stop-color: var(--svg-color--2552c2, #2552C2);
}

.lcawjkgqb {
  fill: var(--svg-color--224bd2, #224BD2);
  d: path("M18.255 23.73c.088-.191.19-.38.258-.505a.1.1 0 0 1 .136-.04l.519.28c.1.056.097.194-.011.236c-.24.092-.533.17-.759.215a.13.13 0 0 1-.143-.185");
}

.lclvhvvqj {
  fill: var(--svg-color--21509b, #21509B);
  d: path("M8.521 14.652c.292-.423.593-.814.743-1c.035.046.308.531.5.875a.25.25 0 0 1-.032.29a13 13 0 0 0-1.084 1.46c-.069.11-.274.068-.28-.063c-.016-.366-.02-.744-.01-1.07a.9.9 0 0 1 .163-.492");
}

.lps8dubve {
  stop-color: var(--svg-color--ffbe6e, #FFBE6E);
  stop-opacity: 0;
}

.lqvaxzbux {
  stop-color: var(--svg-color--4195f0, #4195F0);
}

.lrj11tbwa {
  d: path("M9.891 20.2c.549-.96 1.044-1.933 1.706-2.793a.1.1 0 0 1 .153-.005l1.152 1.298a.1.1 0 0 1 .002.133c-.634.778-1.248 2.298-1.506 3.137a.09.09 0 0 1-.133.056c-.45-.268-1.226-1.102-1.41-1.548c-.038-.092-.013-.192.036-.278");
}

.ls1ll-5ml {
  fill-rule: evenodd;
  d: path("M17.775 7.504c.16.003.208.23.064.3c-.965.478-1.91 1.067-2.64 1.679a.153.153 0 0 1-.238-.052l-.313-.68a.255.255 0 0 1 .073-.304c.32-.259.608-.506 1.39-.913a.5.5 0 0 1 .235-.055z");
}

.lzook0bqj {
  d: path("M23.73 11.351a.207.207 0 0 1-.106.324c-1.907.57-4.166 2.078-4.934 2.677a.207.207 0 0 1-.279-.02l-.468-.509a.194.194 0 0 1 .018-.283c.81-.658 2.862-2.057 5.043-2.799c.118-.04.25 0 .327.1z");
}

.m_5it-7kr {
  stop-color: var(--svg-color--183f98, #183F98);
  stop-opacity: 0;
}

.m6as_jbvu {
  stop-color: var(--svg-color--1a2e9c, #1A2E9C);
  stop-opacity: 0;
}

.mm42u-bci {
  stop-color: var(--svg-color--2667eb, #2667EB);
}

.my79hoagd {
  stop-color: var(--svg-color--2351d4, #2351D4);
}

.n6721tbre {
  fill: var(--svg-color--ed9f63, #ED9F63);
  d: path("m4.413 8.18l5.24 3.351l.758-.93L5.4 6.77a.862.862 0 1 0-.988 1.41");
}

.nd1bdjo5f {
  stop-color: var(--svg-color--2a8de3, #2A8DE3);
  stop-opacity: 0;
}

.nnq9uthin {
  stop-color: var(--svg-color--235dc2, #235DC2);
}

.nu8ta1bsw {
  d: path("M23.783 18.61c.833.166 2.678.921 3.203 2.796c.656 2.344-.812 4.578-2.89 4.578h-8.587a1.71 1.71 0 0 0-1.71 1.711v0a1.71 1.71 0 0 0 1.71 1.711h3.649");
}

.o570a5brb {
  stop-color: var(--svg-color--458ad7, #458AD7);
}

.oliqnpbhw {
  d: path("M12.258 22.728c.394-1.283 1.053-2.648 1.386-3.114a.094.094 0 0 1 .14-.012c.381.344 1.062.93 1.43 1.244c.04.034.046.093.017.136c-.384.577-.843 1.787-1.043 2.468a.25.25 0 0 1-.311.175c-.691-.219-1.334-.576-1.592-.8a.09.09 0 0 1-.027-.097");
}

.oyay3xeql {
  d: path("M18.124 7.643c-1.542.712-2.253 1.253-3.006 1.875a.15.15 0 0 0-.039.181c.203.398.548 1.017.816 1.446a.15.15 0 0 0 .22.036c1.301-1.043 3.194-2.099 4.313-2.552c.094-.038.124-.155.045-.22c-.515-.42-1.655-.675-2.197-.784a.25.25 0 0 0-.152.018");
}

.ozow_wafd {
  stop-color: var(--svg-color--317bde, #317BDE);
  stop-opacity: 0;
}

.p7o9u2boj {
  stop-color: var(--svg-color--ab7942, #AB7942);
  stop-opacity: 0;
}

.pe_j6vf5l {
  stop-color: var(--svg-color--1b2aa6, #1B2AA6);
}

.pqaqosbst {
  stop-color: var(--svg-color--1475d0, #1475D0);
  stop-opacity: 0;
}

.pyuxaqb6t {
  stop-color: var(--svg-color--1167bd, #1167BD);
}

.qccb9lb-j {
  stop-color: var(--svg-color--287ede, #287EDE);
  stop-opacity: 0;
}

.qhyydagjr {
  stop-color: var(--svg-color--31a2fe, #31A2FE);
}

.qse7avb0q {
  stop-color: var(--svg-color--37a6fb, #37A6FB);
  stop-opacity: 0;
}

.qv581m3yu {
  d: path("M11.72 9.317a.23.23 0 0 1 .047-.248c.282-.279.76-.593 1.252-.764a.234.234 0 0 1 .292.142l.042.107c1.04 2.651 4.103 8.055 10.124 10.538l.469.184c.09.035.143.13.11.223c-.118.339-.406.815-.815 1.293a.2.2 0 0 1-.221.054l-.2-.078c-5.1-1.999-9.084-6.412-11.1-11.45");
}

.r7tdhscjs {
  fill: var(--svg-color--193ebd, #193EBD);
  d: path("M17.124 23.807c.159-.566.367-.938.503-1.121a.094.094 0 0 1 .123-.023l.693.4a.153.153 0 0 1 .054.21a3 3 0 0 0-.202.397a.53.53 0 0 1-.437.337l-.53.042a.193.193 0 0 1-.204-.242");
}

.s-jzrotas {
  stop-color: var(--svg-color--183f98, #183F98);
}

.s-our5bst {
  stop-color: var(--svg-color--3699ff, #3699FF);
  stop-opacity: 0;
}

.s8wnov83k {
  stop-color: var(--svg-color--1159a3, #1159A3);
}

.skdj8bb3a {
  stop-color: var(--svg-color--123f81, #123F81);
  stop-opacity: 0;
}

.su9h7jbdx {
  stop-color: var(--svg-color--3281e4, #3281E4);
}

.t5jhxhbsb {
  fill: var(--svg-color--1a4aa7, #1A4AA7);
  d: path("M9.301 19.024a21 21 0 0 1 1.593-2.51a.123.123 0 0 1 .199.003c.153.209.328.44.464.605c.08.098.085.24.008.341c-.596.788-1.232 1.941-1.594 2.656c-.08.155-.285.184-.385.041a6 6 0 0 1-.267-.428a.74.74 0 0 1-.018-.708");
}

.tnbpn7_9n {
  fill: var(--svg-color--2864b2, #2864B2);
  d: path("M8.455 14.396a3.8 3.8 0 0 1 .354-1.336c.036-.072.136-.065.17.007c.095.198.223.45.29.578l-.615.82c-.069.092-.208.045-.2-.069");
}

.txxm7ibdp {
  stop-color: var(--svg-color--2a8de3, #2A8DE3);
}

.u1xxm70nv {
  stop-color: var(--svg-color--15259b, #15259B);
  stop-opacity: 0;
}

.u7g7udb4w {
  fill-rule: evenodd;
  d: path("M11.391 9.355a.253.253 0 0 1 .402.095c2.167 5.263 6.166 9.462 11.174 11.348c.131.05.175.215.083.321l-.407.47a.4.4 0 0 1-.438.113c-6.507-2.445-10.078-8.415-11.334-11.673a.24.24 0 0 1 .068-.272z");
}

.ua4aa6b1e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
}

.uclsr6ztm {
  fill-rule: evenodd;
  d: path("M24.785 17.562a.34.34 0 0 1-.23.262a2.5 2.5 0 0 0-.54.245a.11.11 0 0 1-.11.014l-.934-.418a.097.097 0 0 1-.023-.164c.607-.504 1.284-.78 1.756-.838c.12-.014.208.093.19.211z");
}

.uczevr53o {
  stop-color: var(--svg-color--1a5aab, #1A5AAB);
}

.uhlvyfbfg {
  cx: 16.475px;
  cy: 15.705px;
  r: 7.928px;
  fill: var(--svg-color--071556, #071556);
}

.ui7zkqb3j {
  stop-color: var(--svg-color--2043c7, #2043C7);
}

.uje_7zyns {
  stop-color: var(--svg-color--3588ee, #3588EE);
}

.un4t0ebjn {
  stop-color: var(--svg-color--1a40ba, #1A40BA);
}

.uzr-obb6y {
  fill: var(--svg-color--2c9beb, #2C9BEB);
  d: path("M14.56 8.534a19 19 0 0 1-.228-.59a.143.143 0 0 1 .08-.185a3.2 3.2 0 0 1 1.334-.208c.093.007.106.124.024.169a6.4 6.4 0 0 0-1.128.831a.05.05 0 0 1-.082-.017");
}

.v1611ackt {
  stop-color: var(--svg-color--37a6fb, #37A6FB);
}

.va-h0wb3n {
  stop-color: var(--svg-color--458ad7, #458AD7);
  stop-opacity: 0;
}

.vbg8duboq {
  d: path("M21.517 8.974c.149.083.134.304-.023.37c-1.795.763-4.096 2.225-4.779 2.74a.16.16 0 0 1-.225-.035l-.444-.653a.147.147 0 0 1 .03-.2c.632-.49 2.476-1.8 4.37-2.57a.58.58 0 0 1 .503.033z");
}

.vppfm_o5v {
  stop-color: var(--svg-color--1d498e, #1D498E);
  stop-opacity: 0;
}

.w3s_subrj {
  stop-color: var(--svg-color--44b8ff, #44B8FF);
}

.w6ahkvw3y {
  stop-color: var(--svg-color--267de6, #267DE6);
}

.waysqrx5t {
  stop-color: var(--svg-color--297aef, #297AEF);
}

.wpy0gqbgd {
  d: path("M21.628 9.269c-1.951.824-3.992 2.131-4.92 2.803a.145.145 0 0 0-.034.202c.273.386.73.965 1.067 1.321c.054.057.143.06.203.009c1.393-1.186 3.863-2.488 5.075-2.842c.087-.025.135-.118.094-.198c-.28-.55-.896-1.014-1.243-1.267a.25.25 0 0 0-.242-.028");
}

.wz_3h9bvx {
  stop-color: var(--svg-color--1a47b0, #1A47B0);
}

.x0p1dibuj {
  stop-color: var(--svg-color--317add, #317ADD);
}

.x4pdwvb5l {
  fill: var(--svg-color--ed9f63, #ED9F63);
  d: path("m9.008 3.432l3.193 5.538l1.13-.404l-2.806-5.928a.857.857 0 1 0-1.517.794");
}

.xi7294xot {
  d: path("m9.008 3.432l3.193 5.538l1.13-.404l-2.806-5.928a.857.857 0 1 0-1.517.794");
}

.xnvyu-bsh {
  stop-color: var(--svg-color--123f81, #123F81);
}

.y_uino-9f {
  stop-color: var(--svg-color--1e31bb, #1E31BB);
}

.y9lyp-gal {
  stop-color: var(--svg-color--ab7942, #AB7942);
}

.ygqz2qbix {
  d: path("M24.624 14.608c-1.772.556-2.726 1.202-3.516 1.725a.14.14 0 0 0-.011.232c.43.325 1.191.751 1.657.99a.15.15 0 0 0 .17-.023c.444-.39.911-.643 1.923-.91a.15.15 0 0 0 .113-.14a14 14 0 0 0-.026-1.671a.237.237 0 0 0-.31-.203");
}

.ypfuu3csx {
  stop-color: var(--svg-color--165794, #165794);
  stop-opacity: 0;
}

.z3zh2tn7q {
  stop-color: var(--svg-color--42bcff, #42BCFF);
}

.zs0d6g_8e {
  stop-color: var(--svg-color--0e6ecb, #0E6ECB);
}

</style>
