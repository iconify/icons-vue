<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iL8xb8c)"><path fill="url(#ihhciIe)" clip-rule="evenodd" class="tqg3spiuv"/><path fill="url(#iAcM8rR)" clip-rule="evenodd" class="tqg3spiuv"/><path fill="url(#i6Bsyte)" clip-rule="evenodd" class="tqg3spiuv"/><path fill="url(#isSqZnb)" clip-rule="evenodd" class="tqg3spiuv"/><path fill="url(#ibFBayd)" clip-rule="evenodd" class="tqg3spiuv"/><path fill="url(#iQXxTkd)" clip-rule="evenodd" class="tqg3spiuv"/><path fill="url(#iCgmqhg)" clip-rule="evenodd" class="tqg3spiuv"/><path fill="url(#iPCnYad)" clip-rule="evenodd" class="tqg3spiuv"/><path fill="url(#ijZrHne)" clip-rule="evenodd" class="tqg3spiuv"/></g><path fill="url(#i03MOBb)" class="beqqhlb_f"/><path fill="url(#iNFR1kc)" class="beqqhlb_f"/><path fill="url(#iXbAvFb)" class="beqqhlb_f"/><path fill="url(#iMtUkqc)" class="beqqhlb_f"/><path fill="url(#iBiUVdb)" class="kqgo56bmw"/><path fill="url(#i4hnE1b)" class="kqgo56bmw"/><path fill="url(#iw6hwue)" class="j6gh95b4u"/><path fill="url(#igQAlyn)" class="j6gh95b4u"/><path fill="url(#ip78OEb)" class="j6gh95b4u"/><g filter="url(#iwCyFod)"><path fill="url(#ixUX4Sc)" class="gt5swb36y"/></g><path fill="url(#iP2Jqib)" class="gt5swb36y"/><path fill="url(#ie2Nh2b)" class="gt5swb36y"/><g filter="url(#iwD9gic)"><path fill="url(#iP5q9Me)" class="hy53dfkqz"/></g><rect fill="url(#ixHitbb)" class="f_fjyw2sp"/><rect fill="url(#iTMxI0H)" class="f_fjyw2sp"/><g filter="url(#i64TsYn)"><path fill="url(#iRwcxpe)" class="r30vh0vyr"/></g><g filter="url(#isGLy3c)"><path fill="url(#idzmpee)" class="gzvp9ibnm"/></g><g filter="url(#iU0Kd5b)"><path class="es8e2rb1e"/><path fill="url(#iBB2cPb)" class="ml_xtrk7h"/></g><g filter="url(#iy4wgie)"><path class="pjvprxb_g"/><path fill="url(#ihiGMyc)" class="dg_hnehep"/></g><g filter="url(#iiFNkAc)"><path fill="url(#iQzF19d)" class="m0b-o_bxi"/><path fill="url(#iE3zyWc)" class="m0b-o_bxi"/><path fill="url(#isNsPqe)" class="m0b-o_bxi"/><path fill="url(#iwOCPgb)" class="m0b-o_bxi"/><path fill="url(#iOiCvJM)" class="m0b-o_bxi"/><path fill="url(#iBGKqrd)" class="m0b-o_bxi"/></g><path fill="url(#iRz4KNb)" class="m0b-o_bxi"/><g filter="url(#iMEyr1c)"><path class="slinkcbdf"/></g><g filter="url(#ibUmfve)"><path fill="url(#i0qB2jc)" class="ac1r_9bup"/><path fill="url(#iP2G5Ed)" class="ac1r_9bup"/><path fill="url(#iev78Dc)" class="ac1r_9bup"/><path fill="url(#izvFOie)" class="ac1r_9bup"/></g><path fill="url(#ilMfxta)" class="ac1r_9bup"/><path fill="url(#i8CX5Ee)" class="ac1r_9bup"/><g filter="url(#i07AXLd)"><path class="sstr26r0f"/></g><g filter="url(#iXDBWBd)"><path class="ovciazwpv"/></g><path class="sxvvhsfhy"/><path fill="url(#iWUpcyc)" class="m14jgnbvw"/><path class="z8u6miplq"/><g filter="url(#iwb4Pnb)"><path class="rhnmykbqe"/><path fill="url(#iTllURb)" class="vf--dhhfh"/></g><g filter="url(#ihfkdcD)"><path fill="url(#iGDn4CQ)" class="b6jpvacgg"/></g><path class="xh4ruibji"/><path fill="url(#iF43qwZ)" class="w5loyhsfq"/><path class="u9l39s_6g"/><g filter="url(#iIPcjCc)"><path fill="url(#izDAHGq)" class="sragh6ipp"/></g><g filter="url(#izy2TFc)"><ellipse transform="rotate(-27.914 13.525 10.09)" class="ocv4rvxom"/><ellipse fill="url(#itSCRDc)" transform="rotate(-27.914 13.525 10.09)" class="ramqxhbwi"/></g><g filter="url(#igf97id)"><path fill="url(#idt2wxe)" class="vtw9d08nb"/><path fill="url(#iGNIRvd)" class="vtw9d08nb"/></g><g filter="url(#iNVe0Lb)"><path fill="url(#iQoIfCd)" class="az4unt2ci"/><path fill="url(#iK3CeqL)" class="az4unt2ci"/><path fill="url(#i2x7u4c)" class="az4unt2ci"/></g><g filter="url(#i9Wukpw)"><path stroke="url(#iCe5iqb)" class="qgkq6tb7q"/></g><path clip-rule="evenodd" class="xkp8lg0cw"/><g filter="url(#iq1Jlbc)"><path fill="url(#iw8A12x)" class="mccxzsnbs"/></g><g filter="url(#iRW9k5b)"><rect class="xitwooblv"/></g><g filter="url(#ia4Hu9d)"><rect class="kyyv-3bsk"/></g><g filter="url(#iP3giZd)"><path stroke="url(#i3TJ3uP)" class="skaa0uprr"/></g><g filter="url(#iKErVOb)"><path stroke="url(#i73U7Zb)" class="eq_y2xw8b"/></g><defs><radialGradient id="iAcM8rR" cx="0" cy="0" r="1" gradientTransform="matrix(2.84375 1.53125 -2.16894 4.02803 19.88 14.133)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="i6Bsyte" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.51269 -2.71875 0 11.38 12.852)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="isSqZnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.15625 -6.17186 0 16.01 12.945)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="l56aiabal"/><stop offset="1" class="tnx4w1bew"/></radialGradient><radialGradient id="ibFBayd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2564 1.63048 -1.5831 -1.2199 11.037 11.117)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iQXxTkd" cx="0" cy="0" r="1" gradientTransform="rotate(100.869 1.95 9.387)scale(1.9888 1.60997)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="c42_rqbzh"/><stop offset="1" class="ybrvbdb9p"/></radialGradient><radialGradient id="iCgmqhg" cx="0" cy="0" r="1" gradientTransform="matrix(1.10936 2.14063 -4.07786 2.11331 12.63 3.54)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iPCnYad" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.694 7.233)scale(1.65779 2.31673)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="ijZrHne" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.099 6.648)scale(1.94433 4.2306)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="i03MOBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.625 -11.8762 0 16.002 15.916)" gradientUnits="userSpaceOnUse"><stop class="yzdait1or"/><stop offset="1" class="fh_to2b_k"/></radialGradient><radialGradient id="iNFR1kc" cx="0" cy="0" r="1" gradientTransform="rotate(-90 23.741 .798)scale(8.375)" gradientUnits="userSpaceOnUse"><stop class="we5he9b5x"/><stop offset="1" class="ry9ym0wup"/></radialGradient><radialGradient id="iMtUkqc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.65625 0 0 -3.18983 15.005 15.448)" gradientUnits="userSpaceOnUse"><stop offset=".225" class="pz447cbze"/><stop offset="1" class="a87a47nxn"/></radialGradient><radialGradient id="iBiUVdb" cx="0" cy="0" r="1" gradientTransform="matrix(2.13456 -.2935 1.15245 8.38143 24.387 23.72)" gradientUnits="userSpaceOnUse"><stop class="gq1qbfdiu"/><stop offset="1" class="s2jhqaccf"/></radialGradient><radialGradient id="iw6hwue" cx="0" cy="0" r="1" gradientTransform="rotate(18.435 -63.313 28.921)scale(3.1219 5.27347)" gradientUnits="userSpaceOnUse"><stop class="thab7zb6m"/><stop offset=".965" class="w_io4zdrw"/></radialGradient><radialGradient id="ip78OEb" cx="0" cy="0" r="1" gradientTransform="matrix(.17189 -4.40625 .36187 .01412 8.553 24.54)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="cv_ifqb4z"/><stop offset="1" class="lw76c5ixl"/></radialGradient><radialGradient id="ixUX4Sc" cx="0" cy="0" r="1" gradientTransform="matrix(14.39624 1.34674 -.46749 4.99726 16.668 24.696)" gradientUnits="userSpaceOnUse"><stop class="oqshz6brn"/><stop offset="1" class="b2e5ellij"/></radialGradient><radialGradient id="iP2Jqib" cx="0" cy="0" r="1" gradientTransform="matrix(.70684 1.42914 -5.7496 2.8437 17.493 26.471)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="r_7vpcbwu"/><stop offset="1" class="rxem520qy"/></radialGradient><radialGradient id="ie2Nh2b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.59375 2.52356 -.6861 -1.52084 26.47 23.948)" gradientUnits="userSpaceOnUse"><stop class="kw313ubae"/><stop offset="1" class="rf5xkc8ne"/></radialGradient><radialGradient id="iP5q9Me" cx="0" cy="0" r="1" gradientTransform="rotate(78.93 -6.969 22.296)scale(2.92951 16.093)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="u44n60b3i"/><stop offset=".834" class="wokjsbbtp"/></radialGradient><radialGradient id="ixHitbb" cx="0" cy="0" r="1" gradientTransform="rotate(52.035 -8.836 24.209)scale(2.78619 3.42691)" gradientUnits="userSpaceOnUse"><stop offset=".538" class="obgwgsb_d"/><stop offset=".962" class="gs5mi4b0h"/></radialGradient><radialGradient id="iTMxI0H" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 1 -1.28354 1.60442 13.876 16.479)" gradientUnits="userSpaceOnUse"><stop class="wuv1_cbce"/><stop offset="1" class="q7gy-8gmb"/></radialGradient><radialGradient id="idzmpee" cx="0" cy="0" r="1" gradientTransform="matrix(2.52047 -1.14567 1.3988 3.07737 20.1 11.237)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iBB2cPb" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 41.148 -52.19)scale(1.32105)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="ihiGMyc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08767 0 0 -1.04042 11.284 10.792)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iQzF19d" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.328 7.198)scale(7.25213 9.70685)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iE3zyWc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.13636 1.13 -.95872 -1.81255 17.933 10.954)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="isNsPqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.44384 10.1315 0 16.01 17.197)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="wrs_9y9vq"/><stop offset="1" class="wuz7p6k3a"/></radialGradient><radialGradient id="iwOCPgb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.78779 2.11312 -3.63815 -13.40818 18.941 11.33)" gradientUnits="userSpaceOnUse"><stop offset=".881" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iOiCvJM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.16529 1.43013 0 18.34 9.824)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iBGKqrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37717 1.57832 0 14.067 9.913)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iRz4KNb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.36395 0 0 -4.49017 21.169 11.33)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iP2G5Ed" cx="0" cy="0" r="1" gradientTransform="matrix(-.70626 -2.48066 1.41946 -.40413 16.803 12.067)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="i8CX5Ee" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.275 8.464)scale(1.59476 2.13607)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="iWUpcyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82156 -1.30678 0 18.219 10.188)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iTllURb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.51 .732)scale(.38306 .52738)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iF43qwZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82156 -1.30678 0 13.8 10.188)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="itSCRDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00783 -.5003 .60137 -.00942 13.51 10.41)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idt2wxe" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 5.746 4.999)scale(5.43728 2.37136)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="uv4dr8xud"/></radialGradient><radialGradient id="iGNIRvd" cx="0" cy="0" r="1" gradientTransform="rotate(146.397 5.92 4.353)scale(2.66908 1.32117)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iQoIfCd" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.025 6.978)scale(4.9344 7.01652)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="iK3CeqL" cx="0" cy="0" r="1" gradientTransform="matrix(-.92275 3.22973 -6.78227 -1.93774 18.493 3.994)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="i2x7u4c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.34361 -6.31392 5.65186 -2.99301 17.163 9.491)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><filter id="iL8xb8c" width="15.458" height="15.458" x="8.405" y="1.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4557"/></filter><filter id="iwCyFod" width="19.161" height="7.244" x="8.163" y="22.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.486275 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4557"/></filter><filter id="iwD9gic" width="19.009" height="7.177" x="5.176" y="22.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.552941 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4557"/></filter><filter id="i64TsYn" width="3.409" height="3.509" x="9.635" y="9.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.627451 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4557"/></filter><filter id="isGLy3c" width="3.259" height="3.509" x="19.268" y="8.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4557"/></filter><filter id="iU0Kd5b" width="3.175" height="3.175" x="19.31" y="9.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".25"/></filter><filter id="iy4wgie" width="3.175" height="3.175" x="9.696" y="9.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".25"/></filter><filter id="iiFNkAc" width="10.319" height="11.414" x="10.849" y="5.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4557"/></filter><filter id="iMEyr1c" width="2.901" height="3.716" x="14.394" y="9.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".25"/></filter><filter id="ibUmfve" width="2.401" height="3.216" x="14.809" y="9.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".125"/></filter><filter id="i07AXLd" width="3.037" height="1.302" x="16.966" y="9.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4557"/></filter><filter id="iXDBWBd" width="3.037" height="1.302" x="12.016" y="9.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4557"/></filter><filter id="iwb4Pnb" width=".794" height=".703" x="17.477" y="9.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".05"/></filter><filter id="ihfkdcD" width=".897" height=".92" x="18.328" y="9.821" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".1"/></filter><filter id="iIPcjCc" width=".994" height="1.048" x="13.829" y="9.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".1"/></filter><filter id="izy2TFc" width=".922" height=".711" x="13.064" y="9.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".05"/></filter><filter id="igf97id" width="5.029" height="5.26" x="9.226" y="3.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".375"/></filter><filter id="iNVe0Lb" width="9.234" height="6.155" x="12.537" y="2.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".25"/></filter><filter id="i9Wukpw" width=".852" height="2.031" x="12.931" y="4.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".05"/></filter><filter id="iq1Jlbc" width="1.224" height=".712" x="15.35" y="14.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".05"/></filter><filter id="iRW9k5b" width="2.748" height=".641" x="12.379" y="8.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.317647 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4557"/></filter><filter id="ia4Hu9d" width="2.748" height=".641" x="16.898" y="8.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.317647 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4557"/></filter><filter id="iP3giZd" width="2.77" height=".7" x="16.895" y="8.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".125"/></filter><filter id="iKErVOb" width="2.77" height=".7" x="12.4" y="8.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4557" stdDeviation=".125"/></filter><linearGradient id="ihhciIe" x1="20.762" x2="13.429" y1="3.752" y2="17.364" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iXbAvFb" x1="16.505" x2="16.505" y1="30.289" y2="26.539" gradientUnits="userSpaceOnUse"><stop class="s4ejur1-r"/><stop offset="1" class="b8m56lbmr"/></linearGradient><linearGradient id="i4hnE1b" x1="22.8" x2="23.56" y1="22.786" y2="22.733" gradientUnits="userSpaceOnUse"><stop class="ks4zirblu"/><stop offset="1" class="w9135ub2z"/></linearGradient><linearGradient id="igQAlyn" x1="9.63" x2="8.474" y1="23.789" y2="23.695" gradientUnits="userSpaceOnUse"><stop class="sa_9c2b3h"/><stop offset="1" class="v0otsew1r"/></linearGradient><linearGradient id="iRwcxpe" x1="9.635" x2="12.632" y1="10.881" y2="10.881" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="i0qB2jc" x1="16.009" x2="16.009" y1="12.856" y2="10.141" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iev78Dc" x1="14.95" x2="15.815" y1="12.084" y2="12.19" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="izvFOie" x1="16.009" x2="16.009" y1="12.949" y2="12.332" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="ilMfxta" x1="16.088" x2="16.088" y1="12.923" y2="12.782" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="iGDn4CQ" x1="19.006" x2="18.689" y1="10.242" y2="10.438" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izDAHGq" x1="14.553" x2="14.235" y1="10.242" y2="10.438" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCe5iqb" x1="13.081" x2="13.633" y1="4.516" y2="5.806" gradientUnits="userSpaceOnUse"><stop class="qfg3jinfx"/><stop offset="1" class="y4gwhw_3p"/></linearGradient><linearGradient id="iw8A12x" x1="16.193" x2="15.841" y1="14.369" y2="14.991" gradientUnits="userSpaceOnUse"><stop class="rn1ddlbab"/><stop offset=".736" class="pzma-0biz"/></linearGradient><linearGradient id="i3TJ3uP" x1="19.386" x2="17.089" y1="8.562" y2="8.562" gradientUnits="userSpaceOnUse"><stop class="q_stynbcc"/><stop offset="1" class="amxgxcvbx"/></linearGradient><linearGradient id="i73U7Zb" x1="14.891" x2="12.594" y1="8.562" y2="8.562" gradientUnits="userSpaceOnUse"><stop class="q_stynbcc"/><stop offset="1" class="amxgxcvbx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-pouting" /></template>
<style>
.a87a47nxn {
  stop-color: var(--svg-color--6f3a5f, #6F3A5F);
  stop-opacity: 0;
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ac1r_9bup {
  d: path("m15.622 10.427l-.538 1.721a.546.546 0 0 0 .527.708h.796c.374 0 .637-.36.527-.708l-.538-1.721c-.115-.382-.653-.382-.774 0");
}

.amxgxcvbx {
  stop-color: var(--svg-color--db7e6a, #DB7E6A);
  stop-opacity: 0;
}

.az4unt2ci {
  d: path("M15.771 3.102c-1.147-.254-2.616.825-2.734 1.25c1.561 3.666 3.673 3.262 6.333 2.967c1.592-.177 1.765.548 1.9.9c-.44-4.108-2.885-4.54-5.499-5.117");
}

.b2e5ellij {
  stop-color: var(--svg-color--eba81f, #EBA81F);
}

.b6jpvacgg {
  d: path("M19.026 10.49a.85.85 0 0 0-.235-.47l-.263.29l.12.23z");
}

.b8m56lbmr {
  stop-color: var(--svg-color--7e45bf, #7E45BF);
  stop-opacity: 0;
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.beqqhlb_f {
  d: path("m9.157 24.604l-3.906.183c.578-5.253 5.03-9.34 10.437-9.34h.625c5.415 0 9.872 4.099 10.44 9.363l-4.378-.206v5.187H9.157z");
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.c42_rqbzh {
  stop-color: var(--svg-color--d77016, #D77016);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.cv_ifqb4z {
  stop-color: var(--svg-color--7f5b9c, #7F5B9C);
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dg_hnehep {
  d: path("M11.284 11.88a1.088 1.088 0 1 0 0-2.175a1.088 1.088 0 0 0 0 2.175");
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.eq_y2xw8b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.75 8.562h2.07");
}

.es8e2rb1e {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.897 11.88a1.088 1.088 0 1 0 0-2.175a1.088 1.088 0 0 0 0 2.175");
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.f_fjyw2sp {
  width: 4.223px;
  height: 6.028px;
  x: 13.876px;
  y: 12.542px;
  rx: 2.111px;
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fh_to2b_k {
  stop-color: var(--svg-color--9a6aba, #9A6ABA);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.ft5dv1b6b {
  fill: none;
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gq1qbfdiu {
  stop-color: var(--svg-color--a886e6, #A886E6);
}

.gs5mi4b0h {
  stop-color: var(--svg-color--ffb812, #FFB812);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gt5swb36y {
  d: path("M26.374 28.385c.6-1.05.454-2.812.375-3.597l-3.937-.169c-.413.213-1.526.09-2.031 0l-8.898-1.406c-.617-.117-2.096-.231-2.773.133c-.766.412-1 1.193-.938 1.578c4.271 1.532 12.632 4.563 13.757 4.813c1.82.312 3.695-.04 4.445-1.352");
}

.gzvp9ibnm {
  d: path("M20.897 12.422a1.63 1.63 0 1 0 0-3.259a1.63 1.63 0 0 0 0 3.259");
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hy53dfkqz {
  d: path("M5.626 28.385c-.6-1.05-.454-2.812-.375-3.597l3.937-.169c.413.213 1.526.09 2.031 0l9.672-1.562c.617-.117 1.448-.177 2.125.188c.728.392.7.965.642 1.352a.1.1 0 0 1-.063.077c-4.286 1.54-12.404 4.814-13.524 5.063c-1.82.312-3.695-.04-4.445-1.352");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j6gh95b4u {
  d: path("m5.251 24.787l3.847-.16l.059.183h.031V17.7a10.5 10.5 0 0 0-3.937 7.087");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kqgo56bmw {
  d: path("M22.925 17.79a10.48 10.48 0 0 1 3.827 7.02l-3.827-.18z");
}

.ks4zirblu {
  stop-color: var(--svg-color--8559af, #8559AF);
}

.kw313ubae {
  stop-color: var(--svg-color--ffe548, #FFE548);
}

.kyyv-3bsk {
  width: 2.648px;
  height: 0.541px;
  x: 16.898px;
  y: 8.338px;
  fill: var(--svg-color--c75c21, #C75C21);
  rx: 0.271px;
}

.l56aiabal {
  stop-color: var(--svg-color--9f4d0a, #9F4D0A);
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lw76c5ixl {
  stop-color: var(--svg-color--7f5b9c, #7F5B9C);
  stop-opacity: 0;
}

.m0b-o_bxi {
  d: path("M10.858 9.514h.012l-.01-.269l-.01-.31c.02-.96.58-1.333.82-1.457l.052-.02l.052-.02c.54-.249.976-.683 1.204-1.251l.083-.196a.267.267 0 0 1 .467-.052a3.91 3.91 0 0 0 3.23 1.694h3.26c.183 0 1.096.089 1.15 1.35l-.12 3.111c-.124 2.838-2.34 4.744-5.045 4.744s-4.922-1.906-5.047-4.744z");
}

.m14jgnbvw {
  d: path("M18.22 9.705a.904.904 0 0 1 .872 1.142h-1.746a.907.907 0 0 1 .875-1.142");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mccxzsnbs {
  d: path("M16.474 14.88a.512.512 0 0 0-1.024 0z");
}

.ml_xtrk7h {
  d: path("M20.897 11.88a1.088 1.088 0 1 0 0-2.175a1.088 1.088 0 0 0 0 2.175");
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.obgwgsb_d {
  stop-color: var(--svg-color--ed7f14, #ED7F14);
}

.ocv4rvxom {
  cx: 13.525px;
  cy: 10.091px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oqshz6brn {
  stop-color: var(--svg-color--ffd03d, #FFD03D);
}

.ovciazwpv {
  fill: var(--svg-color--35292e, #35292E);
  d: path("M14.853 10.216c-.269-.473-.678-.846-1.557-.846a1.68 1.68 0 0 0-1.086.373c-.273.22-.236.502-.025.607l.563.322c.66-.214 1.39-.242 2.105-.456");
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pjvprxb_g {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.284 11.88a1.088 1.088 0 1 0 0-2.175a1.088 1.088 0 0 0 0 2.175");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pz447cbze {
  stop-color: var(--svg-color--6f3a5f, #6F3A5F);
}

.pzma-0biz {
  stop-color: var(--svg-color--f2a339, #F2A339);
}

.q_stynbcc {
  stop-color: var(--svg-color--db7e6a, #DB7E6A);
}

.q7gy-8gmb {
  stop-color: var(--svg-color--d77817, #D77817);
  stop-opacity: 0;
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qfg3jinfx {
  stop-color: var(--svg-color--f49f15, #F49F15);
}

.qgkq6tb7q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.081 4.168c.024.246.238 1.171.552 1.731");
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r_7vpcbwu {
  stop-color: var(--svg-color--c26b2d, #C26B2D);
}

.r30vh0vyr {
  d: path("M11.264 12.422a1.63 1.63 0 1 0 0-3.259a1.63 1.63 0 0 0 0 3.259");
}

.ramqxhbwi {
  cx: 13.525px;
  cy: 10.091px;
  rx: 0.395px;
  ry: 0.2px;
}

.rf5xkc8ne {
  stop-color: var(--svg-color--ffe548, #FFE548);
  stop-opacity: 0;
}

.rhnmykbqe {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.154 9.896c.065.086-.07.19-.223.305s-.266.195-.33.11c-.065-.087.007-.25.16-.364s.329-.137.393-.051");
}

.rn1ddlbab {
  stop-color: var(--svg-color--ef9027, #EF9027);
}

.rxem520qy {
  stop-color: var(--svg-color--c26b2d, #C26B2D);
  stop-opacity: 0;
}

.ry9ym0wup {
  stop-color: var(--svg-color--a270cc, #A270CC);
  stop-opacity: 0;
}

.s2jhqaccf {
  stop-color: var(--svg-color--9a69b9, #9A69B9);
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s4ejur1-r {
  stop-color: var(--svg-color--7e45bf, #7E45BF);
}

.sa_9c2b3h {
  stop-color: var(--svg-color--754897, #754897);
}

.skaa0uprr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.245 8.562h2.07");
}

.slinkcbdf {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.612 10.567l-.693 1.721a.546.546 0 0 0 .528.708h.796c.373 0 .637-.36.527-.708l-.538-1.721c-.115-.382-.5-.382-.62 0");
}

.sragh6ipp {
  d: path("M14.623 10.502c0-.292-.237-.487-.302-.545l-.292.282l.18.366z");
}

.sstr26r0f {
  fill: var(--svg-color--383034, #383034);
  d: path("M17.166 10.216c.268-.473.677-.846 1.556-.846c.386 0 .757.107 1.087.373c.272.22.236.502.025.607l-.563.322c-.66-.214-1.39-.242-2.105-.456");
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.sxvvhsfhy {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.43 9.43c.662 0 1.22.455 1.372 1.072a.278.278 0 0 1-.27.345h-2.26a.233.233 0 0 1-.23-.275A1.415 1.415 0 0 1 18.43 9.43");
}

.thab7zb6m {
  stop-color: var(--svg-color--8e71af, #8E71AF);
}

.tnx4w1bew {
  stop-color: var(--svg-color--9f4d0a, #9F4D0A);
  stop-opacity: 0;
}

.tqg3spiuv {
  fill-rule: evenodd;
  d: path("M23.285 12.22c.215-.44.328-.933.328-1.445c0-.473-.097-.917-.272-1.322h.005a3 3 0 0 0-.284-.52l-.002-.003a3.3 3.3 0 0 1-.533-1.793v-.01a3.34 3.34 0 0 0-3.341-3.341a.55.55 0 0 1-.461-.236a3.35 3.35 0 0 0-2.716-1.393a3.35 3.35 0 0 0-2.716 1.393a.57.57 0 0 1-.46.236l-.087.001a3.34 3.34 0 0 0-3.255 3.34v.01A3.3 3.3 0 0 1 8.96 8.93l-.003.004a3.34 3.34 0 0 0-.223 3.286a.52.52 0 0 1 0 .461c-.205.43-.328.912-.328 1.425a3.254 3.254 0 0 0 3.26 3.258h8.69a3.254 3.254 0 0 0 3.258-3.259c0-.512-.123-.994-.328-1.424a.52.52 0 0 1 0-.461M10.87 9.514h-.012l1.213 2.385c.125 2.838 1.233 0 3.938 0s3.885 3.159 4.01.32l1.15-3.237c-.055-1.26-.968-1.349-1.15-1.349h-3.261a3.91 3.91 0 0 1-3.23-1.694a.267.267 0 0 0-.467.052l-.083.196a2.33 2.33 0 0 1-1.308 1.291c-.24.124-.8.496-.82 1.457l.01.31z");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u44n60b3i {
  stop-color: var(--svg-color--ffe243, #FFE243);
}

.u9l39s_6g {
  fill: var(--svg-color--000, #000);
  d: path("M14.315 10.608a.515.515 0 0 0-.518-.517a.515.515 0 0 0-.46.756h.916a.5.5 0 0 0 .062-.239");
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.uv4dr8xud {
  stop-color: var(--svg-color--d9802b, #D9802B);
}

.v0otsew1r {
  stop-color: var(--svg-color--754897, #754897);
  stop-opacity: 0;
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vf--dhhfh {
  d: path("M18.154 9.896c.065.086-.07.19-.223.305s-.266.195-.33.11c-.065-.087.007-.25.16-.364s.329-.137.393-.051");
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vtw9d08nb {
  d: path("M11.053 4.703c.629-.56 1.536-.566 2.045-.476l.408 1.307c-.26-.04-.492.051-.688.238c-.461 1.276-2.048 1.98-2.783 2.172c-.153-1.51-.068-2.274 1.018-3.241");
}

.w_io4zdrw {
  stop-color: var(--svg-color--795993, #795993);
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w3-vy4c8j {
  stop-color: var(--svg-color--e38923, #E38923);
}

.w5loyhsfq {
  d: path("M13.798 9.705a.904.904 0 0 0-.871 1.142h1.745a1 1 0 0 0 .033-.239a.91.91 0 0 0-.908-.903");
}

.w72oynbwi {
  stop-color: var(--svg-color--e38923, #E38923);
  stop-opacity: 0;
}

.w9135ub2z {
  stop-color: var(--svg-color--8559af, #8559AF);
  stop-opacity: 0;
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.we5he9b5x {
  stop-color: var(--svg-color--b188e7, #B188E7);
}

.wokjsbbtp {
  stop-color: var(--svg-color--fcad40, #FCAD40);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wuv1_cbce {
  stop-color: var(--svg-color--d77817, #D77817);
}

.wuz7p6k3a {
  stop-color: var(--svg-color--fba234, #FBA234);
  stop-opacity: 0;
}

.xh4ruibji {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.588 9.43c-.661 0-1.22.455-1.372 1.072a.278.278 0 0 0 .271.345h2.26a.233.233 0 0 0 .23-.275a1.42 1.42 0 0 0-1.389-1.142");
}

.xitwooblv {
  width: 2.648px;
  height: 0.541px;
  x: 12.379px;
  y: 8.338px;
  fill: var(--svg-color--c75c21, #C75C21);
  rx: 0.271px;
}

.xkp8lg0cw {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M16.846 14.21a1.54 1.54 0 0 0-1.673 0a.2.2 0 1 1-.226-.33c.617-.423 1.504-.422 2.124 0a.2.2 0 1 1-.225.33");
}

.y4gwhw_3p {
  stop-color: var(--svg-color--eb7f1c, #EB7F1C);
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.ybrvbdb9p {
  stop-color: var(--svg-color--d77016, #D77016);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.yzdait1or {
  stop-color: var(--svg-color--8755a0, #8755A0);
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z8u6miplq {
  fill: var(--svg-color--000, #000);
  d: path("M17.703 10.608c0-.287.23-.517.518-.517a.515.515 0 0 1 .46.756h-.916a.47.47 0 0 1-.062-.239");
}

</style>
