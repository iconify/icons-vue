<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ieXHEBe)"><path fill="url(#i42bdJb)" class="tace4tbpk"/><path fill="url(#ibr4QQc)" class="tace4tbpk"/><path fill="url(#iwJGUQb)" class="tace4tbpk"/></g><g filter="url(#iLCU3ee)"><path fill="url(#izacige)" class="sgfa1rbjk"/></g><path fill="url(#i8tgQMb)" class="pe1lzd99k"/><path fill="url(#ixfilNd)" class="pe1lzd99k"/><path fill="url(#ipVzoje)" class="pe1lzd99k"/><path fill="url(#i855i0d)" class="pe1lzd99k"/><g filter="url(#iko7dse)"><path class="rt899qbxr"/></g><g filter="url(#iNRX3cb)"><path class="qee9qrb-a"/></g><g filter="url(#iANLBce)"><path fill="url(#iFNSuIj)" class="fslhzxb6y"/><path fill="url(#iKQd1Td)" class="fslhzxb6y"/><path fill="url(#igupTOe)" class="fslhzxb6y"/></g><g filter="url(#ixwxAKb)"><path fill="url(#ioj8Wvb)" class="cgz95w_xc"/><path fill="url(#iZO9grb)" class="cgz95w_xc"/><path fill="url(#ik3mDUd)" class="cgz95w_xc"/></g><g filter="url(#i0jsD5b)"><path fill="url(#izsnqFd)" class="w5ned8_dj"/><path fill="url(#i3kQdvc)" class="w5ned8_dj"/><path fill="url(#i9gudQc)" class="w5ned8_dj"/><path fill="url(#iH2KWhc)" class="w5ned8_dj"/><path fill="url(#izFstOd)" class="w5ned8_dj"/></g><path fill="url(#i2zMIwb)" class="jqm-neb7s"/><path fill="url(#isEkD7d)" class="jqm-neb7s"/><g filter="url(#iRCK4zb)"><path class="h9r1z-bon"/></g><g filter="url(#in00mud)"><path fill="url(#iGefrgQ)" class="cl5p7ebli"/><path fill="url(#iqG9gVd)" class="cl5p7ebli"/></g><g filter="url(#ipABGhe)"><path fill="url(#iMSpGZd)" class="np6o6zdqt"/><path fill="url(#iTGDcfm)" class="np6o6zdqt"/></g><circle fill="url(#iVoNTDe)" class="ejmdq0bvw"/><circle fill="url(#iXxSc8U)" class="ejmdq0bvw"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.39)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.39)" class="movji7bnz"/><circle fill="url(#iWLREMc)" class="qde2s3b0z"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.45)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.45)" class="movji7bnz"/><path fill="url(#ioyOuhc)" class="oxovrxdze"/><g filter="url(#i3sKM0d)"><path class="f7peccyxr"/><path fill="url(#idjxfZp)" class="j26r0vpjq"/><path fill="url(#ikKZnmb)" class="j26r0vpjq"/><path fill="url(#iQziq2d)" class="j26r0vpjq"/><path fill="url(#ivj5E2c)" class="j26r0vpjq"/><path fill="url(#idtJRZd)" class="j26r0vpjq"/></g><path fill="url(#iXDj37C)" class="uyi2cn_rq"/><g filter="url(#ihWkNMc)"><path class="map8u9bfw"/><path fill="url(#igkKNNS)" class="p8ypffh1u"/><path fill="url(#iAppX8b)" class="p8ypffh1u"/></g><g filter="url(#itblhdb)"><path class="rpa19806m"/><path fill="url(#i9q2Ncb)" class="mt1fit0cm"/><path fill="url(#iT2MUNX)" class="mt1fit0cm"/><path fill="url(#iQP5Vmc)" class="mt1fit0cm"/><path fill="url(#ivHlKFc)" class="mt1fit0cm"/><path fill="url(#iF87dkc)" class="mt1fit0cm"/></g><g filter="url(#iqhDEof)"><path fill="url(#iJDeicd)" clip-rule="evenodd" class="j-1mm8iks"/></g><g filter="url(#iM16aob)"><path class="e-ehdobhs"/></g><g filter="url(#i8SBG0b)"><path fill="url(#ipYPB5s)" class="hxg9tfwwt"/><path fill="url(#iQYpTYb)" class="hxg9tfwwt"/></g><g filter="url(#iW0K9sd)"><path stroke="url(#iPez4Ec)" class="diiasj1xd"/></g><g filter="url(#iUPdeFb)"><path stroke="url(#iYKHvQy)" class="kpgsb7bbx"/></g><g filter="url(#igtCGdc)"><path stroke="url(#iSgczve)" class="h6faeg9ph"/></g><g filter="url(#isZS6Je)"><path stroke="url(#iaOUpdd)" class="na45s8szg"/></g><g filter="url(#inlmCpd)"><circle fill="url(#i0b9RDe)" class="lqbimdtnr"/></g><circle fill="url(#i5y3Nkc)" class="lqbimdtnr"/><g filter="url(#iZpBr7S)"><circle fill="url(#iGjiKTc)" class="rchogznqw"/></g><g filter="url(#iqKHKqe)"><circle fill="url(#icvxdLe)" class="mu367fqzs"/><circle fill="url(#iYndjnb)" class="mu367fqzs"/></g><g filter="url(#iouKlqb)"><circle class="twsf00g4g"/><circle fill="url(#iCMvoCe)" class="crr9-vb7l"/><circle fill="url(#iJPZMrc)" class="crr9-vb7l"/></g><g filter="url(#i0TWfDc)"><path fill="url(#i8qP9sb)" class="ehcme1_le"/><path fill="url(#iiwtdPb)" class="ehcme1_le"/><path fill="url(#izcsiAe)" class="ehcme1_le"/></g><path fill="url(#iZaxUve)" class="dj_z3olsc"/><path fill="url(#ixLaARS)" class="dj_z3olsc"/><path fill="url(#iLXIROW)" class="dj_z3olsc"/><g filter="url(#itFRvBp)"><path fill="url(#ibGOQLd)" class="tub_gq5rg"/></g><g filter="url(#ipLCzqe)"><path class="lh-l9zw7m"/><path fill="url(#izp1qae)" class="e0lvxkbiz"/><path fill="url(#iCf36fd)" class="e0lvxkbiz"/><path fill="url(#iPuFoIa)" class="e0lvxkbiz"/><path fill="url(#iLzS4VB)" class="e0lvxkbiz"/></g><g filter="url(#iAoBrPd)"><path class="osjlewbov"/></g><g filter="url(#ipLHjzM)"><path class="rstu5dbco"/><path fill="url(#iVdslrb)" class="rx_emzbvx"/><path fill="url(#izznAWw)" class="rx_emzbvx"/><path fill="url(#isvqqad)" class="rx_emzbvx"/><path fill="url(#iBK7gud)" class="rx_emzbvx"/></g><path stroke="url(#iAZjKKe)" class="qkl0rgdnp"/><g filter="url(#iyY1q2c)"><path class="zmscr-r6r"/><path fill="url(#iPtWqec)" class="jevc-ccmi"/></g><g filter="url(#izGfyBb)"><path class="zzj8f9n5d"/><path fill="url(#i1tQJtc)" class="imd0z6b5d"/></g><path class="elw7h3ljx"/><path fill="url(#iF5VCQE)" class="lqrvugbgh"/><path class="t34l3ccjs"/><g filter="url(#i9PNOsc)"><path class="yjhsj4ynb"/><path fill="url(#iH8ax9d)" class="e84c_-b5e"/></g><g filter="url(#ipGewbe)"><path fill="url(#igb0yqd)" class="uxial92fg"/></g><path class="qo9jj871v"/><path fill="url(#iPFADsb)" class="lohtv9bck"/><path class="asijz3bgx"/><g filter="url(#im3xgXc)"><path fill="url(#ieV3XEl)" class="ek_pucr8x"/></g><g filter="url(#iLA0Vir)"><ellipse transform="rotate(-27.914 13.543 9.898)" class="jbh_6mbnj"/><ellipse fill="url(#iZrcD6d)" transform="rotate(-27.914 13.543 9.898)" class="uyo4culsy"/></g><g filter="url(#iXRJTDZ)"><path stroke="url(#iz8o9cb)" class="pcq1_2buq"/></g><g filter="url(#iRfYklc)"><path stroke="url(#iUUTGMg)" class="q3wmg_jyx"/></g><g filter="url(#i0PUQjc)"><path stroke="url(#idOJkyd)" class="o1e7esk_p"/></g><g filter="url(#iT5dems)"><path fill="url(#iRzm5kc)" clip-rule="evenodd" class="j-1bicbcy"/><path fill="url(#iD4oJqc)" clip-rule="evenodd" class="j-1bicbcy"/></g><defs><radialGradient id="ibr4QQc" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.828 7.011)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="iwJGUQb" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.613)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="i8tgQMb" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.154 15.724)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="ipVzoje" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 27.988)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="i855i0d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.144)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iKQd1Td" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.782)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="igupTOe" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.64 14.62)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iZO9grb" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.763 27.284)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="ik3mDUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.847)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="izsnqFd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.95206 -2.46677 3.46444 -9.76378 21.531 21.566)" gradientUnits="userSpaceOnUse"><stop class="qvobj7b6r"/><stop offset="1" class="zrr9gv88m"/></radialGradient><radialGradient id="i3kQdvc" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.73 16.614)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="shkcotbtg"/><stop offset="1" class="x5158qbnu"/></radialGradient><radialGradient id="i9gudQc" cx="0" cy="0" r="1" gradientTransform="rotate(167.29 7.2 9.214)scale(4.6951 1.22679)" gradientUnits="userSpaceOnUse"><stop offset=".084" class="v56m5tbaw"/><stop offset="1" class="fw6qthi0h"/></radialGradient><radialGradient id="iH2KWhc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07223 -.6455 .5202 -.8641 22.585 20.788)" gradientUnits="userSpaceOnUse"><stop class="ov1bd0bys"/><stop offset="1" class="a0i9ffblh"/><stop offset="1" class="i829wfr2g"/></radialGradient><radialGradient id="izFstOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8125 -.67275 0 14.336 16.681)" gradientUnits="userSpaceOnUse"><stop class="ysbaxhbyq"/><stop offset="1" class="x15soc1he"/></radialGradient><radialGradient id="i2zMIwb" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.7 35.875)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="iqG9gVd" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.154 4.901)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iTGDcfm" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.284)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="iVoNTDe" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.319 11.79)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="iXxSc8U" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.418 14.586)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="iWLREMc" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.355 12.646)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="ioyOuhc" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.353 19.357)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="idjxfZp" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.274 20.211)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="ikKZnmb" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.48 22.987)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="iQziq2d" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.168 9.212)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="ivj5E2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.28 24.784)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="idtJRZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.31 24.565)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="iXDj37C" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.785)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="igkKNNS" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.69)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="iAppX8b" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.704)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="i9q2Ncb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.27)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iT2MUNX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.957)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iJDeicd" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.314 16.624)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="ipYPB5s" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.387 23.831)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="iQYpTYb" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.218)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="i0b9RDe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75472 0 0 3.07077 9.581 10.675)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="i5y3Nkc" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.84 3.243)scale(1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iYndjnb" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.135 10.41)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iCMvoCe" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.722 11.496)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iJPZMrc" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.598 30.583)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iiwtdPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.344 9.404)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="izcsiAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37399 1.70868 0 13.787 9.538)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iLXIROW" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.32774 -10.3217 0 15.87 9.142)" gradientUnits="userSpaceOnUse"><stop offset=".743" class="io6bwfb6c"/><stop offset=".955" class="m3d1nub3m"/></radialGradient><radialGradient id="izp1qae" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.46 -9.995)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="iCf36fd" cx="0" cy="0" r="1" gradientTransform="matrix(3.82451 .35195 -.18924 2.05641 18.7 4.81)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iPuFoIa" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 15.998 2.075)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iLzS4VB" cx="0" cy="0" r="1" gradientTransform="matrix(3.07369 -2.25248 3.52889 4.81545 9.55 8.892)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iBK7gud" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.325 12.281)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iPtWqec" cx="0" cy="0" r="1" gradientTransform="matrix(.10418 -.60322 1.78457 .30822 18.44 8.59)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="i1tQJtc" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.748 -3.598)scale(.61215 1.81109)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iF5VCQE" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.177 9.993)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iH8ax9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 17.949 10.077)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPFADsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.814 9.993)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iZrcD6d" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.79 -1.553)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iD4oJqc" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.672 8.579)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="ieXHEBe" width="21.944" height="26.818" x="4.962" y="3.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="iLCU3ee" width="12.631" height="14.916" x="9.484" y="8.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/><feGaussianBlur result="effect2_foregroundBlur_4002_3417" stdDeviation=".05"/></filter><filter id="iko7dse" width="5.874" height="5.537" x="6.993" y="23.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".5"/></filter><filter id="iNRX3cb" width="4.98" height="4.054" x="18.51" y="24.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".5"/></filter><filter id="iANLBce" width="2.973" height="2.006" x="21.47" y="23.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="ixwxAKb" width="3.281" height="2" x="20.468" y="25.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="i0jsD5b" width="13.965" height="11.381" x="9.149" y="12.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.376471 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="iRCK4zb" width="10.996" height="6.432" x="11.932" y="21.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".5"/></filter><filter id="in00mud" width="2.973" height="2.006" x="7.658" y="23.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="ipABGhe" width="3.266" height="2" x="8.366" y="25.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="i3sKM0d" width="6.218" height="6.789" x="8.343" y="19.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3417" result="effect2_innerShadow_4002_3417"/></filter><filter id="ihWkNMc" width="6.218" height="6.639" x="17.574" y="19.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3417" result="effect2_innerShadow_4002_3417"/></filter><filter id="itblhdb" width="6.702" height="6.417" x="12.683" y="20.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="iqhDEof" width="6.703" height="6.517" x="12.633" y="20.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".15"/></filter><filter id="iM16aob" width="3.2" height="3.2" x="14.271" y="22.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".25"/></filter><filter id="i8SBG0b" width="2.35" height="2.35" x="14.893" y="23.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="iW0K9sd" width="1.458" height="2.505" x="15.848" y="20.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".125"/></filter><filter id="iUPdeFb" width="1.724" height="1.924" x="16.94" y="24.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".125"/></filter><filter id="igtCGdc" width="1.368" height="2.217" x="18.104" y="22.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".125"/></filter><filter id="isZS6Je" width="3.55" height="1.942" x="15.171" y="17.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".25"/></filter><filter id="inlmCpd" width="3.539" height="3.339" x="9.581" y="9.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="iZpBr7S" width="2.99" height="2.99" x="9.756" y="9.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".25"/></filter><filter id="iqKHKqe" width="3.589" height="3.589" x="19.094" y="8.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="iouKlqb" width="2.99" height="2.99" x="19.268" y="9.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".25"/></filter><filter id="i0TWfDc" width="10.373" height="12.177" x="10.841" y="5.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="itFRvBp" width="8.246" height="7.066" x="14.168" y="3.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation="1"/></filter><filter id="ipLCzqe" width="12.601" height="8.543" x="9.698" y="1.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="iAoBrPd" width="3.26" height="4.181" x="14.129" y="9.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".375"/></filter><filter id="ipLHjzM" width="2.377" height="3.181" x="14.81" y="9.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".125"/></filter><filter id="iyY1q2c" width="2.979" height="1.873" x="17.18" y="7.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="izGfyBb" width="2.98" height="1.873" x="12.033" y="7.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><filter id="i9PNOsc" width=".787" height=".696" x="17.443" y="9.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".05"/></filter><filter id="ipGewbe" width=".891" height=".913" x="18.282" y="9.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".1"/></filter><filter id="im3xgXc" width=".986" height="1.04" x="13.841" y="9.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".1"/></filter><filter id="iLA0Vir" width=".913" height=".704" x="13.087" y="9.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".05"/></filter><filter id="iXRJTDZ" width="3.099" height="1.681" x="17.034" y="7.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".25"/></filter><filter id="iRfYklc" width="3.177" height="1.738" x="11.815" y="7.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".25"/></filter><filter id="i0PUQjc" width="1.008" height="2.269" x="10.833" y="5.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3417" stdDeviation=".125"/></filter><filter id="iT5dems" width="15.448" height="4.54" x="8.283" y="2.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3417"/></filter><linearGradient id="i42bdJb" x1="26.906" x2="11.7" y1="11.488" y2="21.488" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="izacige" x1="20.7" x2="10.387" y1="17.394" y2="17.394" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="ixfilNd" x1="14.887" x2="14.887" y1="30.863" y2="29.582" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="iFNSuIj" x1="23.649" x2="21.867" y1="25.785" y2="24.374" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="ioj8Wvb" x1="22.95" x2="21.169" y1="27.369" y2="25.675" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="isEkD7d" x1="12.653" x2="13.255" y1="29.253" y2="28.91" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="iGefrgQ" x1="7.856" x2="9.361" y1="24.269" y2="26.088" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iMSpGZd" x1="9.062" x2="10.843" y1="27.368" y2="25.683" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="iQP5Vmc" x1="14.919" x2="16.7" y1="27.132" y2="22.863" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="ivHlKFc" x1="13.356" x2="16.981" y1="22.894" y2="23.582" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iF87dkc" x1="17.231" x2="16.325" y1="26.894" y2="25.144" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iPez4Ec" x1="16.477" x2="16.477" y1="20.816" y2="22.824" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iYKHvQy" x1="17.286" x2="18.153" y1="24.871" y2="26.074" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="iSgczve" x1="18.728" x2="18.728" y1="22.402" y2="24.019" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iaOUpdd" x1="16.132" x2="20.117" y1="19.014" y2="17.842" gradientUnits="userSpaceOnUse"><stop class="b63i8aczf"/><stop offset="1" class="v85e7pbqp"/></linearGradient><linearGradient id="iGjiKTc" x1="11.251" x2="10.61" y1="10.954" y2="10.954" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="icvxdLe" x1="21.849" x2="21.031" y1="9.584" y2="12.12" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="i8qP9sb" x1="20.034" x2="12.398" y1="11.065" y2="12.203" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iZaxUve" x1="10.603" x2="12.484" y1="13.761" y2="13.693" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="ixLaARS" x1="20.919" x2="19.806" y1="12.919" y2="12.822" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="ibGOQLd" x1="15.467" x2="23.61" y1="8.08" y2="5.165" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="iVdslrb" x1="15.134" x2="16.072" y1="11.724" y2="11.724" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="izznAWw" x1="16.937" x2="15.911" y1="12.046" y2="12.031" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="isvqqad" x1="16.193" x2="16.193" y1="12.788" y2="12.215" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iAZjKKe" x1="14.961" x2="15.396" y1="14.403" y2="13.716" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="igb0yqd" x1="18.955" x2="18.641" y1="10.047" y2="10.241" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ieV3XEl" x1="14.558" x2="14.244" y1="10.047" y2="10.24" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iz8o9cb" x1="18.97" x2="18.55" y1="7.907" y2="7.049" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iUUTGMg" x1="13.666" x2="12.477" y1="7.78" y2="7.281" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="idOJkyd" x1="11.337" x2="11.337" y1="5.766" y2="7.922" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><linearGradient id="iRzm5kc" x1="20.481" x2="8.544" y1="3.644" y2="7.331" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-veil-medium" /></template>
<style>
.a0i9ffblh {
  stop-color: var(--svg-color--7c4f3f, #7C4F3F);
  stop-opacity: 0;
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.asijz3bgx {
  fill: var(--svg-color--000, #000);
  d: path("M14.323 10.409a.51.51 0 0 0-.51-.512a.51.51 0 0 0-.455.747h.904a.5.5 0 0 0 .061-.236");
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.b63i8aczf {
  stop-color: var(--svg-color--c49987, #C49987);
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.cgz95w_xc {
  d: path("M20.61 25.8c.678-.599 1.716-.535 2.297.112l.69.735c.063.067.083.205-.023.27c-.91.563-1.996.492-2.66-.27l-.42-.583a.11.11 0 0 1 .009-.15z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl5p7ebli {
  d: path("M10.52 25.287c-.063-.898-.843-1.585-1.721-1.534l-.99.059c-.121 0-.162.157-.149.207c.176.966.961 1.703 2 1.633l.768-.098a.11.11 0 0 0 .102-.117z");
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.crr9-vb7l {
  cx: 20.763px;
  cy: 10.675px;
  r: 0.995px;
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.diiasj1xd {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.019c.324 0 .758.376.758.86v.945");
}

.dj_z3olsc {
  d: path("M10.84 8.624c0-.266.108-.586.322-.746l.161-.16c.269-.214.376-.534.376-.854v-.853c0-.266.16-.48.429-.533c.644-.16 1.984-.427 3.915-.427s3.272.267 3.916.427c.214.053.429.267.429.533v.853c0 .32.16.64.375.854c.502.352.47.545.43.96c-.054.533-.108 1.44-.108 1.44h.018l-.266 3.957c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.002c-.14-1.817-.2-3.639-.366-5.452");
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e-ehdobhs {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.35a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0lvxkbiz {
  d: path("m20.817 4.198l.429.213c.75.374 1.18 1.227 1.019 2.134l-.59 3.04c-.053.313-.26.524-.572.532h-.018s.054-.906.107-1.44c.044-.432-.032-.564-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.266-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.271.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.854l-.16.16c-.215.16-.322.48-.322.746c.053.587.107 1.44.107 1.44l-.05-.001a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.43-.213c.267-.16.535-.373.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.266 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.e84c_-b5e {
  d: path("M18.113 9.705c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ehcme1_le {
  d: path("m10.899 10.063l.049.001s-.054-.853-.107-1.44c0-.266.107-.586.322-.746l.16-.16c.269-.214.376-.534.376-.854v-.853c0-.266.16-.48.429-.533c.644-.16 1.984-.427 3.915-.427s3.272.267 3.916.427c.214.053.429.267.429.533v.853c0 .32.16.64.375.854c.502.352.47.545.43.96c-.054.533-.108 1.44-.108 1.44h.018l-.266 3.957c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.002z");
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ejmdq0bvw {
  cx: 9.168px;
  cy: 20.492px;
  r: 0.762px;
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.ek_pucr8x {
  d: path("M14.627 10.304c0-.289-.234-.48-.297-.539l-.289.279l.178.361z");
}

.elw7h3ljx {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.386 9.245c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.271c.126-.64.69-1.127 1.37-1.127");
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f7peccyxr {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.753c-.076-.155-.018-.354.098-.418c.854-.403 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.028.355.183l.753 1.631l.133.311c.111.293.303.84.336 1.135c.152 1.231-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.fslhzxb6y {
  d: path("M21.48 25.287c.063-.898.843-1.585 1.721-1.534l.99.059c.121 0 .162.157.149.207c-.176.966-.961 1.703-2 1.633l-.768-.098a.11.11 0 0 1-.102-.117z");
}

.ft5dv1b6b {
  fill: none;
}

.fw6qthi0h {
  stop-color: var(--svg-color--844e52, #844E52);
  stop-opacity: 0;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.h6faeg9ph {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.566c.307.135.83.616.461 1.453");
}

.h9r1z-bon {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.401c.096.054.144.22.081.348l-.668 1.39c-.181.389-.526.926-.809 1.178c-.687.638-1.466.645-2.21.3a2.4 2.4 0 0 1-.481-.292a.97.97 0 0 1-.407.893c-.466.324-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.002l-.201.313a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.416l.298-.438a.042.042 0 0 0-.027-.064l-.308-.055a.97.97 0 0 1-.799-1.174a.97.97 0 0 1 1.248-.707l.516.175a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.557.514 1.048 1.08 1.04c.574-.008.81-1.664.81-1.062v.467c0 .029.028.049.055.04l.458-.156a1 1 0 0 1 .223-.058l.036-.085l1.043.854c.063-.13.19-.198.295-.152c.711.327.494-.417.288.728c-.022.123.015.13.098.03c.74-.9 1.97-1.696 2.682-1.36");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.hxg9tfwwt {
  d: path("M15.993 25.218a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.i829wfr2g {
  stop-color: var(--svg-color--8b604a, #8B604A);
  stop-opacity: 0;
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.imd0z6b5d {
  d: path("M12.225 7.955h.002l.002-.002l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.16a.534.534 0 1 1-.166 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.679-.824");
}

.io6bwfb6c {
  stop-color: var(--svg-color--945d69, #945D69);
  stop-opacity: 0;
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j-1bicbcy {
  fill-rule: evenodd;
  d: path("M15.972 4.356c-3.812 0-5.694 1.657-6.334 2.38a.775.775 0 0 1-1.16-1.028c.88-.996 3.165-2.902 7.494-2.902c4.41 0 6.608 1.915 7.54 2.876a.775.775 0 1 1-1.112 1.08c-.735-.758-2.556-2.406-6.428-2.406");
}

.j-1mm8iks {
  fill-rule: evenodd;
  d: path("M13.709 24.328a.913.913 0 0 1-.753-1.107a.91.91 0 0 1 1.178-.668l.617.21a.3.3 0 0 0 .396-.302l-.03-.484v-.007q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.56a.3.3 0 0 0 .396.285l.551-.188l.007-.002c.516-.194 1.023.046 1.16.559c.14.532-.183 1.093-.687 1.183l-.466.103a.3.3 0 0 0-.178.469l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.3-1.012.16-1.32-.295l-.316-.423a.3.3 0 0 0-.493.018l-.247.383l-.005.008a.91.91 0 0 1-1.294.33l-.001-.001a.92.92 0 0 1-.227-1.336l.005-.006l.362-.533a.3.3 0 0 0-.196-.464l-.369-.067z");
}

.j26r0vpjq {
  d: path("M8.528 22.753c-.076-.155-.018-.354.098-.418c.854-.403 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.028.355.183l.753 1.631l.133.311c.111.293.303.84.336 1.135c.152 1.231-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jbh_6mbnj {
  cx: 13.543px;
  cy: 9.898px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jevc-ccmi {
  d: path("M19.718 7.955h-.002l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.24-.14-.42-.21a2.83 2.83 0 0 0-1.492-.16a.534.534 0 1 0 .166 1.055c.398-.063.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.jqm-neb7s {
  d: path("m13.196 29.925l-2.547-3.837l5.25-3.475l5.828 2.909l-2.922 4.403z");
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kpgsb7bbx {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.785l.907 1.18");
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.lh-l9zw7m {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m20.817 4.198l.429.213c.75.374 1.18 1.227 1.019 2.134l-.59 3.04c-.053.313-.26.524-.572.532h-.018s.054-.906.107-1.44c.044-.432-.032-.564-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.266-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.271.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.854l-.16.16c-.215.16-.322.48-.322.746c.053.587.107 1.44.107 1.44l-.05-.001a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.43-.213c.267-.16.535-.373.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.266 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lohtv9bck {
  d: path("M13.812 9.516a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.lqbimdtnr {
  cx: 11.251px;
  cy: 10.675px;
  r: 1.669px;
}

.lqrvugbgh {
  d: path("M18.179 9.516a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.127");
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m3d1nub3m {
  stop-color: var(--svg-color--96636d, #96636D);
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.map8u9bfw {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.753c.076-.155.018-.354-.098-.418c-.854-.403-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.631c-.044.107-.088.204-.132.311c-.111.293-.303.84-.336 1.135c-.152 1.231.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mt1fit0cm {
  d: path("M12.712 23.166c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.562a.05.05 0 0 0 .066.047l.55-.187c.64-.24 1.31.058 1.49.729c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.08l.307.422c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.414a.05.05 0 0 0-.081.003l-.242.376c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.527a.05.05 0 0 0-.032-.077l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.mu367fqzs {
  cx: 20.763px;
  cy: 10.675px;
  r: 1.669px;
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.na45s8szg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.839c.395.01 1.357-.063 2.05-.442");
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.np6o6zdqt {
  d: path("M11.39 25.8c-.678-.599-1.716-.535-2.298.112l-.69.735c-.062.067-.04.22.024.27c.91.563 1.996.492 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o1e7esk_p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.466 5.864v.898c-.008.148-.07.48-.258.622");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o9qsnlb6c {
  stop-color: var(--svg-color--1b572f, #1B572F);
  stop-opacity: 0;
}

.obmju7b-z {
  stop-color: var(--svg-color--d0246b, #D0246B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.osjlewbov {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.723 10.553l-.82 1.7c-.102.349.142.698.488.698h.737c.346 0 .59-.354.488-.699l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.ov1bd0bys {
  stop-color: var(--svg-color--8b604a, #8B604A);
}

.oxovrxdze {
  d: path("m11.186 26.295l2.71-1.12l-.67-1.62c-.41-1-1.1-1.692-1.988-2.11c-.465-.19-.717.058-.797.238c-.3.82-.081 2.137.085 3.002z");
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.p8ypffh1u {
  d: path("M23.457 22.753c.076-.155.018-.354-.098-.418c-.854-.403-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.631c-.044.107-.088.204-.132.311c-.111.293-.303.84-.336 1.135c-.152 1.231.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pcq1_2buq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.659 7.81c.43-.075 1.268-.053 1.849.398");
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pe1lzd99k {
  d: path("M27 29.926v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06V17.8c0 .29-.2.55-.48.61C8.61 19.55 5 23.726 5 28.926v1z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q3wmg_jyx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.44 8.33c.327-.29 1.041-.594 1.927-.453");
}

.qde2s3b0z {
  cx: 10.18px;
  cy: 21.57px;
  r: 0.762px;
}

.qee9qrb-a {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 25.966c.78-.46 1.787-.2 2.235.545l.538.852c.048.078.043.217-.074.261c-1 .38-2.053.105-2.561-.77l-.302-.651a.11.11 0 0 1 .037-.146z");
}

.qkl0rgdnp {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.636 13.432a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24c.344.521.942.868 1.624.868s1.28-.347 1.625-.868a.19.19 0 0 0-.021-.242a.2.2 0 0 0-.241-.04a2.94 2.94 0 0 1-1.363.324c-.5 0-.968-.118-1.362-.323Z");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qo9jj871v {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.605 9.245c-.653 0-1.204.45-1.354 1.058c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .227-.27a1.4 1.4 0 0 0-1.37-1.128");
}

.qvobj7b6r {
  stop-color: var(--svg-color--c2977c, #C2977C);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rchogznqw {
  cx: 11.251px;
  cy: 10.675px;
  r: 0.995px;
}

.rpa19806m {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.166c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.562a.05.05 0 0 0 .066.047l.55-.187c.64-.24 1.31.058 1.49.729c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.08l.307.422c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.414a.05.05 0 0 0-.081.003l-.242.376c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.527a.05.05 0 0 0-.032-.077l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.rstu5dbco {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.616 10.39l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.rt899qbxr {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.137c.879-.051 1.658.636 1.72 1.534l.009.116c.31.044.61.175.862.397l.107.114a.11.11 0 0 1 .01.15l-.42.582c-.665.763-1.75.834-2.66.271c-.064-.05-.086-.203-.024-.27l.69-.735q.136-.151.302-.26c-.906-.06-1.574-.75-1.735-1.633c-.013-.05.028-.207.15-.207z");
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.rx_emzbvx {
  d: path("m15.616 10.39l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.sgfa1rbjk {
  d: path("M9.984 15.848c0-4.854 2.694-7.281 6.016-7.281s6.016 2.323 6.016 7.28v7.436H9.984z");
}

.shkcotbtg {
  stop-color: var(--svg-color--a97b73, #A97B73);
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t34l3ccjs {
  fill: var(--svg-color--000, #000);
  d: path("M17.668 10.408c0-.283.227-.51.511-.51a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.06-.236");
}

.tace4tbpk {
  d: path("M5.062 16.425c0-8.812 4.89-13.218 10.922-13.218s10.922 4.218 10.922 13.218v13.5H5.062z");
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tub_gq5rg {
  d: path("m19.962 5.051l-3.078 1.026a1.047 1.047 0 0 0 .47 2.031l3.06-.41z");
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.twsf00g4g {
  cx: 20.763px;
  cy: 10.675px;
  r: 0.995px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.uxial92fg {
  d: path("M18.974 10.291a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.uyi2cn_rq {
  d: path("m20.799 26.295l-2.71-1.12l.67-1.62c.41-1 1.1-1.692 1.987-2.11c.466-.19.718.058.798.238c.3.82.081 2.137-.085 3.002z");
}

.uyo4culsy {
  cx: 13.543px;
  cy: 9.898px;
  rx: 0.389px;
  ry: 0.197px;
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v56m5tbaw {
  stop-color: var(--svg-color--844e52, #844E52);
}

.v85e7pbqp {
  stop-color: var(--svg-color--c49987, #C49987);
  stop-opacity: 0;
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w5ned8_dj {
  d: path("M9.15 20.458a11.2 11.2 0 0 1 4.31-2.047c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1V17.8c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.062a8.44 8.44 0 0 1-6.852 3.504a8.44 8.44 0 0 1-6.864-3.519");
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.x15soc1he {
  stop-color: var(--svg-color--966c60, #966C60);
  stop-opacity: 0;
}

.x5158qbnu {
  stop-color: var(--svg-color--a97b73, #A97B73);
  stop-opacity: 0;
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.yjhsj4ynb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.113 9.705c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.ysbaxhbyq {
  stop-color: var(--svg-color--966c60, #966C60);
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zmscr-r6r {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M19.718 7.955h-.002l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.24-.14-.42-.21a2.83 2.83 0 0 0-1.492-.16a.534.534 0 1 0 .166 1.055c.398-.063.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.zrr9gv88m {
  stop-color: var(--svg-color--9e755f, #9E755F);
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

.zzj8f9n5d {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M12.225 7.955h.002l.002-.002l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.16a.534.534 0 1 1-.166 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.679-.824");
}

</style>
