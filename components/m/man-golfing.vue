<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ioKuVMb)"><path fill="url(#i4qjsyb)" clip-rule="evenodd" class="v4kcuirrp"/></g><g filter="url(#i9d5b3b)"><path class="z71hdhjff"/><path fill="url(#iWbMd3c)" class="kdlv9_bls"/><path fill="url(#iMfDZRc)" class="kdlv9_bls"/></g><path fill="url(#iM2ZBoc)" class="kdlv9_bls"/><path fill="url(#i4fo1Jb)" class="bkr7869lt"/><path fill="url(#ickfMge)" class="bkr7869lt"/><path fill="url(#iLNdLQc)" class="bkr7869lt"/><g filter="url(#i0xmA0c)"><path class="zglchomad"/></g><path class="gjxwbhbmv"/><path fill="url(#izFkmcc)" class="w9zd-yl1d"/><path fill="url(#i7Bqyee)" class="w9zd-yl1d"/><path fill="url(#izvgqde)" class="w9zd-yl1d"/><path fill="url(#iapI9xB)" class="w9zd-yl1d"/><g filter="url(#iru5UIb)"><path class="j0qja52ua"/></g><path fill="url(#iKTBNfe)" class="caxdafbwx"/><path fill="url(#iORIMUV)" class="caxdafbwx"/><path fill="url(#ixqdxab)" class="caxdafbwx"/><path fill="url(#iQ7kcpb)" class="caxdafbwx"/><path fill="url(#icNiFBb)" class="caxdafbwx"/><path fill="url(#isPtC8w)" class="caxdafbwx"/><path fill="url(#i9jqAQU)" class="caxdafbwx"/><path fill="url(#iHdzpne)" class="jezzs576s"/><path fill="url(#i9oWtXd)" class="jezzs576s"/><path fill="url(#iHpNLxK)" class="jezzs576s"/><path fill="url(#iUNnOdd)" class="jezzs576s"/><path fill="url(#iGpvEme)" class="jezzs576s"/><rect fill="url(#imBkStd)" transform="rotate(-26.783 20.65 4.038)" class="mskngdcth"/><rect fill="url(#iWqrKUb)" transform="rotate(-26.783 21.084 3.778)" class="o61xwibfm"/><rect fill="url(#iLFjrQc)" transform="rotate(-26.783 21.603 3.532)" class="qn24elbha"/><rect fill="url(#ij6t2dd)" transform="rotate(-26.783 22.173 3.278)" class="r_m5h2bes"/><rect fill="url(#i6gArie)" transform="rotate(60 21.976 4.31)" class="m33noxexr"/><g filter="url(#iHTMP8d)"><path class="s5_pn7jby"/><path fill="url(#iX3Jhte)" class="vwuow_o2v"/></g><g filter="url(#iLyPEwR)"><path fill="url(#iO4ydeb)" class="rzse29jtu"/><path fill="url(#ib7pYIc)" class="rzse29jtu"/><path fill="url(#i5WZhGc)" class="rzse29jtu"/></g><g filter="url(#iUcPREd)"><path class="cpw4_mbst"/></g><g filter="url(#iLdxaXc)"><path stroke="url(#iKhVJuc)" class="yzcwl7btv"/></g><g filter="url(#inRdONc)"><path fill="url(#iGgtjsX)" class="xqdsusm2m"/></g><circle fill="url(#i5hNcae)" transform="rotate(-28.394 12.886 7.133)" class="rqp-6e03y"/><g filter="url(#i6hT5Rb)"><circle fill="url(#id7EAQb)" transform="rotate(-28.394 12.886 7.132)" class="d3xfob9cr"/></g><g filter="url(#iJ4BTJu)"><circle fill="url(#iyE0Fgb)" transform="rotate(-28.394 16.383 5.242)" class="z7_c_lb_j"/><circle fill="url(#iygLHYd)" transform="rotate(-28.394 16.383 5.242)" class="z7_c_lb_j"/></g><g filter="url(#iaw68tc)"><circle transform="rotate(-28.394 16.383 5.242)" class="x-1t1ccta"/><circle fill="url(#iXRw8Ae)" transform="rotate(-28.394 16.383 5.242)" class="qx9ghhkfo"/><circle fill="url(#iMu8Brb)" transform="rotate(-28.394 16.383 5.242)" class="qx9ghhkfo"/></g><path fill="url(#iUzL2eB)" class="ncdsrkb3j"/><path fill="url(#iaC0FxO)" class="ncdsrkb3j"/><path fill="url(#iANWg8c)" class="ncdsrkb3j"/><path fill="url(#iF5xbId)" class="ncdsrkb3j"/><path fill="url(#iMaY4fe)" class="ncdsrkb3j"/><path fill="url(#iLtoELd)" class="ncdsrkb3j"/><g filter="url(#iVLk3ze)"><path class="t74reu7dx"/></g><g filter="url(#iXCOrHY)"><path class="vvlplsbjn"/><path fill="url(#ib9eo9d)" class="lnyk6x-bs"/><path fill="url(#iCwuCcc)" class="lnyk6x-bs"/><path fill="url(#iSzmo4o)" class="lnyk6x-bs"/></g><g filter="url(#ilWjr4b)"><path stroke="url(#iVM5yKb)" class="ybwhezbaj"/></g><path class="k8alrsb3s"/><path class="iwio6bczt"/><path fill="url(#iti88Ed)" class="z1w_hpbnu"/><path class="hl3j42bpz"/><g filter="url(#i3GzA3c)"><path class="xr-frx4ha"/><path fill="url(#iTFp0fc)" class="i2xaiebhq"/></g><g filter="url(#icrvmce)"><path fill="url(#isf8gld)" class="d_0zv270f"/></g><path class="zymwyoupt"/><path fill="url(#i4MElcB)" class="b1tmgebsc"/><path class="bdzupxbgt"/><g filter="url(#iuePo3d)"><path fill="url(#iXN7Sob)" class="tp151lkys"/></g><g filter="url(#ieFGUgd)"><ellipse transform="rotate(-56.308 13.574 6.391)" class="l50gu4bav"/><ellipse fill="url(#iVgVfBe)" transform="rotate(-56.308 13.574 6.391)" class="tlxo32brv"/></g><g filter="url(#ixctARb)"><path clip-rule="evenodd" class="ll8mz2b3v"/></g><g filter="url(#i2weUTb)"><path clip-rule="evenodd" class="dzikotyir"/></g><path fill="url(#iWasSMI)" class="w3_s37nup"/><path fill="url(#iDJ5sMe)" class="hd29i3bui"/><path fill="url(#ipVwDcJ)" class="hd29i3bui"/><g filter="url(#iZUpDqe)"><path fill="url(#i120pQe)" class="pl2knmb6f"/><path fill="url(#i476JDl)" class="pl2knmb6f"/></g><path fill="url(#iLEB2Kb)" class="snvf_6bih"/><path fill="url(#ilkijwb)" class="snvf_6bih"/><path fill="url(#iuzquNd)" class="snvf_6bih"/><path fill="url(#iluONzm)" class="snvf_6bih"/><defs><radialGradient id="iWbMd3c" cx="0" cy="0" r="1" gradientTransform="rotate(146.915 8.782 5.886)scale(4.92324 2.04943)" gradientUnits="userSpaceOnUse"><stop class="ba1yb3bji"/><stop offset="1" class="kgrhzo17p"/></radialGradient><radialGradient id="iM2ZBoc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 -.0625 .23626 5.43402 6.51 13.617)" gradientUnits="userSpaceOnUse"><stop class="wn-t5ndzy"/><stop offset="1" class="ben4f0bqs"/></radialGradient><radialGradient id="iLNdLQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .16016 -.21807 -.37232 24.841 2.87)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="i42zc8m6u"/><stop offset="1" class="dsumrvbgt"/></radialGradient><radialGradient id="i7Bqyee" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 -.46876 .24583 -.45888 14.134 29.475)" gradientUnits="userSpaceOnUse"><stop class="ynlfw99ba"/><stop offset="1" class="in-vfpgwh"/></radialGradient><radialGradient id="izvgqde" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 .85157 -1.15842 -1.0415 12.743 26.968)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="vkrof_bbk"/><stop offset="1" class="h8hiq33uv"/></radialGradient><radialGradient id="iapI9xB" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 .15625 -.58594 3.04687 11.368 28.367)" gradientUnits="userSpaceOnUse"><stop class="ilg8l_bzj"/><stop offset="1" class="s2j02zbkr"/></radialGradient><radialGradient id="iORIMUV" cx="0" cy="0" r="1" gradientTransform="matrix(2.71873 -2.53127 .81258 .87276 13.166 27.93)" gradientUnits="userSpaceOnUse"><stop class="pcvpzjboo"/><stop offset="1" class="qe_2d-buv"/></radialGradient><radialGradient id="ixqdxab" cx="0" cy="0" r="1" gradientTransform="matrix(2.54688 -2.64063 .2894 .27913 12.275 26.273)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="kxzgmzb5t"/><stop offset="1" class="xhu8yhbcw"/></radialGradient><radialGradient id="iQ7kcpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 0 0 -5.02098 17.369 21.617)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="keljo6scd"/><stop offset="1" class="ps4m-ab9c"/></radialGradient><radialGradient id="icNiFBb" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 -.98437 1.15192 .05485 17.619 18.289)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="w5oxhdc5r"/><stop offset="1" class="ebs2-pbbe"/></radialGradient><radialGradient id="isPtC8w" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 0 0 7.6823 17.978 22.976)" gradientUnits="userSpaceOnUse"><stop class="j_l_30buh"/><stop offset="1" class="xi8fv135v"/></radialGradient><radialGradient id="i9jqAQU" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -3.34375 1.20794 1.23052 13.666 27.992)" gradientUnits="userSpaceOnUse"><stop class="ddjhanboc"/><stop offset="1" class="uu7_gub8n"/></radialGradient><radialGradient id="iHdzpne" cx="0" cy="0" r="1" gradientTransform="rotate(150.356 8.577 7.599)scale(4.42262 6.15908)" gradientUnits="userSpaceOnUse"><stop class="no0_3dbdi"/><stop offset="1" class="truekjbvb"/></radialGradient><radialGradient id="i9oWtXd" cx="0" cy="0" r="1" gradientTransform="matrix(.57404 2.73801 -4.6268 .97003 17.28 7.254)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="kdxlabb_n"/><stop offset="1" class="x9_x14ckq"/></radialGradient><radialGradient id="iUNnOdd" cx="0" cy="0" r="1" gradientTransform="matrix(.87501 1.59375 -2.6006 1.4278 15.291 7.96)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="v2g8x4brb"/><stop offset="1" class="we0trlbug"/></radialGradient><radialGradient id="iGpvEme" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -.01563 .0588 6.46896 13.478 10.367)" gradientUnits="userSpaceOnUse"><stop class="qg0h4w_kv"/><stop offset="1" class="iich1wbqp"/></radialGradient><radialGradient id="imBkStd" cx="0" cy="0" r="1" gradientTransform="matrix(.09624 .94236 -.56384 .05758 20.9 4.252)" gradientUnits="userSpaceOnUse"><stop class="hcmpzwvfn"/><stop offset="1" class="tzgzt3b1l"/></radialGradient><radialGradient id="iWqrKUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 21.76 4.447)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="euzbypbyq"/><stop offset="1" class="ob4ztkbap"/></radialGradient><radialGradient id="iLFjrQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 22.28 4.2)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="euzbypbyq"/><stop offset="1" class="ob4ztkbap"/></radialGradient><radialGradient id="ij6t2dd" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 22.849 3.947)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="euzbypbyq"/><stop offset="1" class="ob4ztkbap"/></radialGradient><radialGradient id="i6gArie" cx="0" cy="0" r="1" gradientTransform="matrix(-.02457 .47352 -.46721 -.02424 22.37 4.461)" gradientUnits="userSpaceOnUse"><stop class="usai76iql"/><stop offset=".931" class="muua73y8y"/></radialGradient><radialGradient id="iX3Jhte" cx="0" cy="0" r="1" gradientTransform="matrix(3.80388 .30087 -.62375 7.88601 17.576 5.601)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="t_a14bpou"/><stop offset="1" class="ojy1jndng"/></radialGradient><radialGradient id="ib7pYIc" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 .21242 -.56203 4.5475 14.04 9.773)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="v__i2ebru"/><stop offset="1" class="yrm14tb3b"/></radialGradient><radialGradient id="i5WZhGc" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 .51562 -1.9883 .18075 16.181 8.757)" gradientUnits="userSpaceOnUse"><stop class="hnewum4zo"/><stop offset="1" class="j297-pbqp"/></radialGradient><radialGradient id="i5hNcae" cx="0" cy="0" r="1" gradientTransform="matrix(.7333 0 0 1.28328 12.188 7.133)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iygLHYd" cx="0" cy="0" r="1" gradientTransform="matrix(.34545 -.25154 .2871 .39429 16.538 5.132)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iXRw8Ae" cx="0" cy="0" r="1" gradientTransform="rotate(-61.467 12.88 -10.97)scale(.71773 .42009)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iMu8Brb" cx="0" cy="0" r="1" gradientTransform="matrix(.10824 .10714 -.13812 .13953 16.383 5.242)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iaC0FxO" cx="0" cy="0" r="1" gradientTransform="matrix(1.9202 3.55226 -4.05603 2.19252 14.464 5.448)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="v71hqib9z"/><stop offset=".916" class="snzqtmgtz"/><stop offset="1" class="p40p06bts"/></radialGradient><radialGradient id="iF5xbId" cx="0" cy="0" r="1" gradientTransform="rotate(-118.394 9.187 -1.916)scale(.54619 .67222)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iMaY4fe" cx="0" cy="0" r="1" gradientTransform="rotate(-118.394 8.613 -.967)scale(.5812 .72277)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iLtoELd" cx="0" cy="0" r="1" gradientTransform="rotate(61.606 2.953 14.017)scale(1.78351 2.81721)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="q4ajq1t1d"/><stop offset="1" class="zjm96qmni"/></radialGradient><radialGradient id="iVM5yKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.1156 -.23547 .70642 -.3468 15.397 7.68)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iti88Ed" cx="0" cy="0" r="1" gradientTransform="matrix(.17928 .33167 -.39244 .21213 15.363 5.629)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iTFp0fc" cx="0" cy="0" r="1" gradientTransform="matrix(-.14447 -.0637 .0877 -.1989 15.23 5.582)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4MElcB" cx="0" cy="0" r="1" gradientTransform="rotate(61.607 1.432 14.786)scale(.37704 .44613)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iVgVfBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00323 -.20601 .24764 -.00388 13.567 6.522)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipVwDcJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.47287 -.36725 .20636 -.26571 15.887 4.346)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="r24hnpb7d"/><stop offset="1" class="eo8gvvf_z"/></radialGradient><radialGradient id="i120pQe" cx="0" cy="0" r="1" gradientTransform="rotate(-31.917 16.609 -18.966)scale(3.2214 11.9372)" gradientUnits="userSpaceOnUse"><stop class="fn7-6xayh"/><stop offset="1" class="chayuvnap"/></radialGradient><radialGradient id="i476JDl" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.625 1.10767 0 15.132 4.617)" gradientUnits="userSpaceOnUse"><stop class="sylx2mbjo"/><stop offset="1" class="nav-8e2lo"/></radialGradient><radialGradient id="iLEB2Kb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 1.17364 -1.119 -2.38363 14.82 3.974)" gradientUnits="userSpaceOnUse"><stop class="blekadc8f"/><stop offset="1" class="c6xk9jx7z"/></radialGradient><radialGradient id="ilkijwb" cx="0" cy="0" r="1" gradientTransform="matrix(.15625 -2.375 3.6798 .24209 12.194 5.898)" gradientUnits="userSpaceOnUse"><stop class="jjpmu-56c"/><stop offset="1" class="ldm9khd7d"/></radialGradient><radialGradient id="iuzquNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.41126 -.92188 2.0385 -.9094 13.866 4.804)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o2ca957_x"/><stop offset="1" class="a7xagmxua"/></radialGradient><radialGradient id="iluONzm" cx="0" cy="0" r="1" gradientTransform="matrix(.32812 .53125 -2.88379 1.78116 12.866 2.945)" gradientUnits="userSpaceOnUse"><stop class="uw0kegb-q"/><stop offset="1" class="ydllxhbat"/></radialGradient><filter id="ioKuVMb" width="8.471" height="7.176" x="16.221" y="3.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.580392 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22986"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.545098 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22986" result="effect2_innerShadow_3987_22986"/></filter><filter id="i9d5b3b" width="18.187" height="14.194" x="6.907" y="2.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.454902 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22986"/></filter><filter id="i0xmA0c" width="4.793" height="2.27" x="18.177" y="27.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.188235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22986"/></filter><filter id="iru5UIb" width="8.989" height="12.477" x="12.161" y="15.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.635294 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22986"/></filter><filter id="iHTMP8d" width="7.553" height="7.567" x="14.351" y="3.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.658824 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22986"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.537255 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22986" result="effect2_innerShadow_3987_22986"/></filter><filter id="iLyPEwR" width="3.395" height="2.909" x="14.313" y="8.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.4 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22986"/></filter><filter id="iUcPREd" width="1.789" height="3.497" x="8.087" y="12.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22986" stdDeviation=".125"/></filter><filter id="iLdxaXc" width="2.601" height="13.601" x="18.427" y="15.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22986" stdDeviation=".4"/></filter><filter id="inRdONc" width="2.563" height="7.453" x="15.025" y="16.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22986" stdDeviation=".375"/></filter><filter id="i6hT5Rb" width="1.831" height="1.831" x="11.97" y="6.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22986" stdDeviation=".25"/></filter><filter id="iJ4BTJu" width="1.645" height="1.646" x="15.685" y="4.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22986"/></filter><filter id="iaw68tc" width="1.831" height="1.831" x="15.467" y="4.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22986" stdDeviation=".25"/></filter><filter id="iVLk3ze" width="2.243" height="2.62" x="13.747" y="5.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22986" stdDeviation=".375"/></filter><filter id="iXCOrHY" width="1.085" height="1.313" x="14.331" y="5.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22986" stdDeviation=".05"/></filter><filter id="ilWjr4b" width="1.596" height="1.188" x="14.416" y="6.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22986" stdDeviation=".05"/></filter><filter id="i3GzA3c" width=".374" height=".467" x="14.962" y="5.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22986" stdDeviation=".05"/></filter><filter id="icrvmce" width=".615" height=".617" x="15.233" y="5.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22986" stdDeviation=".1"/></filter><filter id="iuePo3d" width=".667" height=".657" x="13.586" y="5.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22986" stdDeviation=".1"/></filter><filter id="ieFGUgd" width=".426" height=".485" x="13.361" y="6.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22986" stdDeviation=".05"/></filter><filter id="ixctARb" width="1.291" height=".827" x="14.318" y="4.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.156863 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22986"/></filter><filter id="i2weUTb" width="1.117" height="1.136" x="12.52" y="5.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.156863 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22986"/></filter><filter id="iZUpDqe" width="4.109" height="2.52" x="11.954" y="3.728" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.396078 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22986"/></filter><linearGradient id="i4qjsyb" x1="23.013" x2="19.956" y1="5.042" y2="11.047" gradientUnits="userSpaceOnUse"><stop class="ksevddbvl"/><stop offset=".799" class="d30rw76zq"/></linearGradient><linearGradient id="iMfDZRc" x1="12.493" x2="12.822" y1="9.473" y2="9.945" gradientUnits="userSpaceOnUse"><stop offset=".349" class="lr97j31fb"/><stop offset="1" class="azn0z--js"/></linearGradient><linearGradient id="i4fo1Jb" x1="24.916" x2="22.775" y1="2.992" y2="4.304" gradientUnits="userSpaceOnUse"><stop class="ds3hm--8v"/><stop offset="1" class="bq7w62n5j"/></linearGradient><linearGradient id="ickfMge" x1="23.884" x2="23.619" y1="3.992" y2="3.461" gradientUnits="userSpaceOnUse"><stop class="seeiowbir"/><stop offset="1" class="tw6dxpb7y"/></linearGradient><linearGradient id="izFkmcc" x1="12.697" x2="12.697" y1="30.328" y2="29.656" gradientUnits="userSpaceOnUse"><stop class="dhem-xbnm"/><stop offset="1" class="zn47ozbfv"/></linearGradient><linearGradient id="iKTBNfe" x1="20.478" x2="19.884" y1="22.867" y2="22.835" gradientUnits="userSpaceOnUse"><stop class="ieaclmdnn"/><stop offset="1" class="p3yd_be1u"/></linearGradient><linearGradient id="iHpNLxK" x1="17.279" x2="17.279" y1="16.273" y2="13.085" gradientUnits="userSpaceOnUse"><stop offset=".039" class="ptputobcp"/><stop offset="1" class="br5umybnw"/></linearGradient><linearGradient id="iO4ydeb" x1="16.011" x2="16.011" y1="8.656" y2="10.867" gradientUnits="userSpaceOnUse"><stop class="bw1hkxbcb"/><stop offset="1" class="tesa8u_3j"/></linearGradient><linearGradient id="iKhVJuc" x1="19.744" x2="19.744" y1="16.898" y2="27.804" gradientUnits="userSpaceOnUse"><stop class="hd06b2knh"/><stop offset="1" class="ggughpb3d"/></linearGradient><linearGradient id="iGgtjsX" x1="16.306" x2="16.306" y1="18.335" y2="24.898" gradientUnits="userSpaceOnUse"><stop class="y6ovumr8k"/><stop offset="1" class="t-eeezbdl"/></linearGradient><linearGradient id="id7EAQb" x1="12.886" x2="12.618" y1="7.249" y2="7.249" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iyE0Fgb" x1="16.837" x2="16.495" y1="4.786" y2="5.846" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iUzL2eB" x1="16.192" x2="13.611" y1="5.53" y2="7.466" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iANWg8c" x1="13.261" x2="14.051" y1="8.396" y2="7.825" gradientUnits="userSpaceOnUse"><stop class="e7tiq4b9r"/><stop offset="1" class="wa00b45sw"/></linearGradient><linearGradient id="ib9eo9d" x1="14.522" x2="14.867" y1="6.746" y2="6.56" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iCwuCcc" x1="15.249" x2="14.869" y1="6.507" y2="6.705" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iSzmo4o" x1="15.123" x2="15.009" y1="6.927" y2="6.717" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="isf8gld" x1="15.593" x2="15.516" y1="5.371" y2="5.504" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXN7Sob" x1="13.977" x2="13.9" y1="6.245" y2="6.378" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWasSMI" x1="12.355" x2="12.136" y1="6.415" y2="6.533" gradientUnits="userSpaceOnUse"><stop class="nhc87rgbt"/><stop offset="1" class="h1q2j_bib"/></linearGradient><linearGradient id="iDJ5sMe" x1="16.203" x2="16.304" y1="4.335" y2="4.28" gradientUnits="userSpaceOnUse"><stop class="pw4-s-b5m"/><stop offset="1" class="rfipqcbwy"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-golfing" /></template>
<style>
.a7xagmxua {
  stop-color: var(--svg-color--1a7ccc, #1A7CCC);
  stop-opacity: 0;
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.azn0z--js {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
  stop-opacity: 0;
}

.b1tmgebsc {
  d: path("M13.597 6.198a.373.373 0 0 0-.092.585l.633-.343a.375.375 0 0 0-.541-.243");
}

.ba1yb3bji {
  stop-color: var(--svg-color--a99797, #A99797);
}

.bdzupxbgt {
  fill: var(--svg-color--000, #000);
  d: path("M13.963 6.424a.213.213 0 0 0-.29-.086a.213.213 0 0 0-.018.365l.332-.18a.2.2 0 0 0-.024-.1");
}

.ben4f0bqs {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
  stop-opacity: 0;
}

.bkr7869lt {
  d: path("m21.765 5.257l-.5-.866l3.122-1.859a.4.4 0 0 1 .548.14l.102.171a.4.4 0 0 1-.139.549z");
}

.blekadc8f {
  stop-color: var(--svg-color--30a2e5, #30A2E5);
}

.bq7w62n5j {
  stop-color: var(--svg-color--482a5b, #482A5B);
}

.br5umybnw {
  stop-color: var(--svg-color--366bc5, #366BC5);
  stop-opacity: 0;
}

.bw1hkxbcb {
  stop-color: var(--svg-color--2d9de0, #2D9DE0);
}

.c6xk9jx7z {
  stop-color: var(--svg-color--1b96dc, #1B96DC);
}

.caxdafbwx {
  d: path("M14.522 23.947a1 1 0 0 0 .275-.712l-.167-7.29h6.02l-.312 12.476H18.18l-.259-10.002a.255.255 0 0 0-.509-.004c-.049 1.195-.13 3.454-.13 4.585c0 1.212-.693 2.213-1.04 2.562L13.77 27.85a.32.32 0 0 1-.317.081a2.2 2.2 0 0 1-.718-.424c-.252-.224-.439-.552-.547-.795a.36.36 0 0 1 .078-.392z");
}

.chayuvnap {
  stop-color: var(--svg-color--1d78b8, #1D78B8);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpw4_mbst {
  stroke: var(--svg-color--c3b8c3, #C3B8C3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.51 12.914a.53.53 0 0 0 0 .539c.13.237.718 1.277.96 1.715c.05.102.111.355-.039.542");
}

.d_0zv270f {
  d: path("M15.648 5.457a.35.35 0 0 0-.177-.124l-.038.156l.088.06z");
}

.d30rw76zq {
  stop-color: var(--svg-color--f5aa27, #F5AA27);
}

.d3xfob9cr {
  cx: 12.886px;
  cy: 7.132px;
  r: 0.415px;
}

.ddjhanboc {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
}

.dhem-xbnm {
  stop-color: var(--svg-color--442563, #442563);
}

.ds3hm--8v {
  stop-color: var(--svg-color--533d66, #533D66);
}

.dsumrvbgt {
  stop-color: var(--svg-color--615273, #615273);
  stop-opacity: 0;
}

.dzikotyir {
  fill: var(--svg-color--a0354c, #A0354C);
  fill-rule: evenodd;
  d: path("M13.517 5.691c-.278.119-.392.314-.413.374a.197.197 0 0 1-.373-.128c.056-.165.249-.446.631-.609a.197.197 0 0 1 .155.363");
}

.e7tiq4b9r {
  stop-color: var(--svg-color--ffc651, #FFC651);
}

.ebs2-pbbe {
  stop-color: var(--svg-color--9c8cad, #9C8CAD);
  stop-opacity: 0;
}

.eo8gvvf_z {
  stop-color: var(--svg-color--ef8a2f, #EF8A2F);
  stop-opacity: 0;
}

.euzbypbyq {
  stop-color: var(--svg-color--fdc83c, #FDC83C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.fn7-6xayh {
  stop-color: var(--svg-color--3e82bc, #3E82BC);
}

.ft5dv1b6b {
  fill: none;
}

.ggughpb3d {
  stop-color: var(--svg-color--a599b3, #A599B3);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjxwbhbmv {
  fill: var(--svg-color--47385d, #47385D);
  d: path("M11.595 27.789c0-.807.458-1.16.688-1.235l1.367 1.18v1.283a.5.5 0 0 0 .187.39l.203.163c.128.094.297.238.25.414c-.082.172-.25.195-.539.195h-1.506a.65.65 0 0 1-.65-.65z");
}

.h1q2j_bib {
  stop-color: var(--svg-color--d28d46, #D28D46);
}

.h8hiq33uv {
  stop-color: var(--svg-color--271938, #271938);
  stop-opacity: 0;
}

.hcmpzwvfn {
  stop-color: var(--svg-color--e0a524, #E0A524);
}

.hd06b2knh {
  stop-color: var(--svg-color--a89eb3, #A89EB3);
}

.hd29i3bui {
  d: path("m16.288 4.304l-.286-.528l-.44.238a.8.8 0 0 0 .293.17c.127.035.23.158.272.236l.247.529c.028-.015.082-.045.09-.144c.013-.156-.14-.44-.176-.5");
}

.hl3j42bpz {
  fill: var(--svg-color--000, #000);
  d: path("M15.192 5.76a.213.213 0 0 1 .087-.29a.213.213 0 0 1 .315.184l-.332.18a.2.2 0 0 1-.07-.074");
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hnewum4zo {
  stop-color: var(--svg-color--2f89b9, #2F89B9);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.i2xaiebhq {
  d: path("M15.216 5.412c.04.019.012.083-.021.155c-.033.071-.059.123-.099.104c-.04-.018-.046-.091-.013-.163c.033-.071.093-.114.133-.096");
}

.i42zc8m6u {
  stop-color: var(--svg-color--615273, #615273);
}

.ieaclmdnn {
  stop-color: var(--svg-color--a19ca8, #A19CA8);
}

.iich1wbqp {
  stop-color: var(--svg-color--56a2e0, #56A2E0);
  stop-opacity: 0;
}

.ilg8l_bzj {
  stop-color: var(--svg-color--655e6d, #655E6D);
}

.in-vfpgwh {
  stop-color: var(--svg-color--403451, #403451);
  stop-opacity: 0;
}

.iwio6bczt {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.225 5.189a.584.584 0 0 1 .708.12a.115.115 0 0 1-.03.178l-.82.444a.096.096 0 0 1-.138-.055a.584.584 0 0 1 .28-.687");
}

.j_l_30buh {
  stop-color: var(--svg-color--5d5467, #5D5467);
}

.j0qja52ua {
  fill: var(--svg-color--9785a9, #9785A9);
  d: path("M14.522 23.947a1 1 0 0 0 .275-.712l-.167-7.29h6.02l-.312 12.476H18.18l-.259-10.002a.255.255 0 0 0-.509-.004c-.049 1.195-.13 3.454-.13 4.585c0 1.212-.693 2.213-1.04 2.562L13.77 27.85a.32.32 0 0 1-.317.081a2.2 2.2 0 0 1-.718-.424c-.252-.224-.439-.552-.547-.795a.36.36 0 0 1 .078-.392z");
}

.j297-pbqp {
  stop-color: var(--svg-color--2f89b9, #2F89B9);
  stop-opacity: 0;
}

.jezzs576s {
  d: path("M13.927 9.835c.176-1.285.703-1.862 1-2.07c.51-.358 1.664-.945 3.336 0c1.758 1.094 2.404 4.057 2.375 5.375v2.805h-6v-3.242c0-.488-.105-.743-.258-.961c-.144-.258-.52-.98-.453-1.907");
}

.jjpmu-56c {
  stop-color: var(--svg-color--4199e0, #4199E0);
}

.k8alrsb3s {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.253 7.34a1.3 1.3 0 0 1-.574.154c-.065.002-.088.088-.032.116c.224.12.506.129.75-.003a.79.79 0 0 0 .414-.626c.006-.064-.078-.09-.114-.037a1.25 1.25 0 0 1-.444.396");
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kdlv9_bls {
  d: path("M8.948 12.89a.35.35 0 0 0-.125.474l.88 1.545a1 1 0 0 1-.373 1.364l-.115.065a1 1 0 0 1-1.364-.374l-.728-1.277a1.65 1.65 0 0 1 .617-2.25l.343-.196l16.303-9.709a.4.4 0 0 1 .549.14l.102.171a.4.4 0 0 1-.14.549z");
}

.kdxlabb_n {
  stop-color: var(--svg-color--3090bc, #3090BC);
}

.keljo6scd {
  stop-color: var(--svg-color--827a8b, #827A8B);
}

.kgrhzo17p {
  stop-color: var(--svg-color--a99797, #A99797);
  stop-opacity: 0;
}

.ksevddbvl {
  stop-color: var(--svg-color--fdc631, #FDC631);
}

.kxzgmzb5t {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l50gu4bav {
  cx: 13.574px;
  cy: 6.391px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.162px;
  ry: 0.082px;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.ldm9khd7d {
  stop-color: var(--svg-color--4199e0, #4199E0);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll8mz2b3v {
  fill: var(--svg-color--a2374b, #A2374B);
  fill-rule: evenodd;
  d: path("M14.825 4.984c.252-.168.477-.156.539-.14a.197.197 0 0 0 .097-.383c-.169-.043-.51-.036-.855.195a.197.197 0 1 0 .22.328");
}

.lnyk6x-bs {
  d: path("m14.434 6.16l.142.73c.03.15.195.227.33.154l.29-.156a.226.226 0 0 0 .052-.36l-.533-.52c-.117-.115-.312-.01-.281.152");
}

.lr97j31fb {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
}

.m33noxexr {
  width: 0.737px;
  height: 1.252px;
  x: 21.976px;
  y: 4.309px;
  rx: 0.369px;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mskngdcth {
  width: 0.692px;
  height: 1.157px;
  x: 20.651px;
  y: 4.038px;
  rx: 0.346px;
}

.muua73y8y {
  stop-color: var(--svg-color--f3ae21, #F3AE21);
}

.nav-8e2lo {
  stop-color: var(--svg-color--3386c4, #3386C4);
  stop-opacity: 0;
}

.ncdsrkb3j {
  d: path("M12.316 6.4c-.053-.098-.118-.263-.07-.365l-.066-.17c.056-.132.177-.105.114-.222l-.17-.314a.22.22 0 0 1 .052-.281a7 7 0 0 1 1.354-.935a7 7 0 0 1 1.525-.621a.24.24 0 0 1 .263.11l.17.314a.53.53 0 0 0 .308.24c.254.029.281.106.348.267c.29.693.63 1.37.942 2.055c.293.682.027 1.412-.583 1.741l-1.18.638c-.63.34-1.367.153-1.777-.466c-.41-.637-.87-1.323-1.23-1.991");
}

.nhc87rgbt {
  stop-color: var(--svg-color--e47729, #E47729);
}

.no0_3dbdi {
  stop-color: var(--svg-color--53aff7, #53AFF7);
}

.o2ca957_x {
  stop-color: var(--svg-color--1a7ccc, #1A7CCC);
}

.o61xwibfm {
  width: 0.692px;
  height: 1.157px;
  x: 21.084px;
  y: 3.778px;
  rx: 0.346px;
}

.ob4ztkbap {
  stop-color: var(--svg-color--eaa22a, #EAA22A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojy1jndng {
  stop-color: var(--svg-color--ffd540, #FFD540);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p3yd_be1u {
  stop-color: var(--svg-color--a49faa, #A49FAA);
  stop-opacity: 0;
}

.p40p06bts {
  stop-color: var(--svg-color--f18a66, #F18A66);
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pcvpzjboo {
  stop-color: var(--svg-color--937da8, #937DA8);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl2knmb6f {
  d: path("M12.389 5.252c-.189.25-.328.529-.435.858l.252.106c.19.078.41.01.52-.163c.197-.306.58-.784 1.239-1.14a3.4 3.4 0 0 1 1.631-.411a.42.42 0 0 0 .418-.345l.05-.269a3 3 0 0 0-.957-.106a3.66 3.66 0 0 0-2.718 1.47");
}

.ps4m-ab9c {
  stop-color: var(--svg-color--827a8b, #827A8B);
  stop-opacity: 0;
}

.ptputobcp {
  stop-color: var(--svg-color--366bc5, #366BC5);
}

.pw4-s-b5m {
  stop-color: var(--svg-color--ffa829, #FFA829);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q4ajq1t1d {
  stop-color: var(--svg-color--d47e31, #D47E31);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qe_2d-buv {
  stop-color: var(--svg-color--937da8, #937DA8);
  stop-opacity: 0;
}

.qg0h4w_kv {
  stop-color: var(--svg-color--56a2e0, #56A2E0);
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qn24elbha {
  width: 0.692px;
  height: 1.157px;
  x: 21.603px;
  y: 3.532px;
  rx: 0.346px;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qx9ghhkfo {
  cx: 16.383px;
  cy: 5.242px;
  r: 0.415px;
}

.r_m5h2bes {
  width: 0.692px;
  height: 1.157px;
  x: 22.173px;
  y: 3.278px;
  rx: 0.346px;
}

.r24hnpb7d {
  stop-color: var(--svg-color--ef8a2f, #EF8A2F);
}

.rfipqcbwy {
  stop-color: var(--svg-color--ffbb3c, #FFBB3C);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rqp-6e03y {
  cx: 12.886px;
  cy: 7.133px;
  r: 0.698px;
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.rzse29jtu {
  d: path("M16.001 8.87c.328-.03.652-.124.848-.214l.86 2.195c-.235.121-1.716.594-2.54.43s-1.02-1.196-.73-1.739c.273-.609 1.118-.63 1.562-.671");
}

.s2j02zbkr {
  stop-color: var(--svg-color--655e6d, #655E6D);
  stop-opacity: 0;
}

.s5_pn7jby {
  fill: var(--svg-color--ffc131, #FFC131);
  d: path("M19.317 5.992a.5.5 0 0 0-.015-.254a5 5 0 0 0-.227-.524c-.02-.088-.025-.29.11-.39a.36.36 0 0 1 .336-.055a.45.45 0 0 1 .207-.285c.134-.072.298-.03.363 0c.018-.066.09-.209.23-.246a.52.52 0 0 1 .356.058c.04-.075.169-.224.36-.214c.238.011.374.261.41.449c.035.187.093.433.152.578s.117.605-.09 1.2l-.001-.001c-.454 1.885-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.009-3.297 1.083a1.1 1.1 0 0 1-.193-2.192c.636-.056 1.522-.243 2.304-.744c.683-.436 1.327-1.135 1.66-2.316");
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.seeiowbir {
  stop-color: var(--svg-color--482c58, #482C58);
}

.snvf_6bih {
  d: path("M13.29 2.74c.529-.286 1.122-.403 1.672-.186c.422.166.866.653 1.101 1.334a3 3 0 0 0-.956-.106a3.66 3.66 0 0 0-2.718 1.47a2.9 2.9 0 0 0-.435.857c-.443-.573-.605-1.208-.513-1.652c.12-.578.542-1.011 1.072-1.297z");
}

.snzqtmgtz {
  stop-color: var(--svg-color--ee8952, #EE8952);
}

.sylx2mbjo {
  stop-color: var(--svg-color--3386c4, #3386C4);
}

.t_a14bpou {
  stop-color: var(--svg-color--ffd540, #FFD540);
  stop-opacity: 0;
}

.t-eeezbdl {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
  stop-opacity: 0;
}

.t74reu7dx {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m14.506 6.2l.036.787c.032.149.19.229.318.16L15.131 7c.127-.068.146-.247.04-.354l-.52-.525c-.114-.118-.18-.083-.146.078");
}

.tesa8u_3j {
  stop-color: var(--svg-color--3083ea, #3083EA);
}

.tlxo32brv {
  cx: 13.574px;
  cy: 6.391px;
  rx: 0.162px;
  ry: 0.082px;
}

.tp151lkys {
  d: path("M14.053 6.325c-.057-.106-.182-.13-.216-.139l-.05.16l.136.097z");
}

.truekjbvb {
  stop-color: var(--svg-color--347fda, #347FDA);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tw6dxpb7y {
  stop-color: var(--svg-color--482c58, #482C58);
  stop-opacity: 0;
}

.tzgzt3b1l {
  stop-color: var(--svg-color--bb7701, #BB7701);
}

.usai76iql {
  stop-color: var(--svg-color--fcc540, #FCC540);
}

.uu7_gub8n {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
  stop-opacity: 0;
}

.uw0kegb-q {
  stop-color: var(--svg-color--4195cb, #4195CB);
}

.v__i2ebru {
  stop-color: var(--svg-color--579fde, #579FDE);
}

.v2g8x4brb {
  stop-color: var(--svg-color--246c9d, #246C9D);
}

.v4kcuirrp {
  fill-rule: evenodd;
  d: path("M20.961 7.78c.852-1.082.481-2.213.22-2.677l1.915-1.082c.467.828 1.242 3.027-.406 5.12c-.89 1.13-2.33 1.567-3.484 1.753c-1.198.193-2.37.158-2.985.134l.084-2.198c.599.023 1.583.048 2.55-.108c1.012-.163 1.746-.485 2.106-.942");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v71hqib9z {
  stop-color: var(--svg-color--ee8952, #EE8952);
  stop-opacity: 0;
}

.vkrof_bbk {
  stop-color: var(--svg-color--271938, #271938);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vvlplsbjn {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m14.434 6.16l.142.73c.03.15.195.227.33.154l.29-.156a.226.226 0 0 0 .052-.36l-.533-.52c-.117-.115-.312-.01-.281.152");
}

.vwuow_o2v {
  d: path("M19.317 5.992a.5.5 0 0 0-.015-.254a5 5 0 0 0-.227-.524c-.02-.088-.025-.29.11-.39a.36.36 0 0 1 .336-.055a.45.45 0 0 1 .207-.285c.134-.072.298-.03.363 0c.018-.066.09-.209.23-.246a.52.52 0 0 1 .356.058c.04-.075.169-.224.36-.214c.238.011.374.261.41.449c.035.187.093.433.152.578s.117.605-.09 1.2l-.001-.001c-.454 1.885-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.009-3.297 1.083a1.1 1.1 0 0 1-.193-2.192c.636-.056 1.522-.243 2.304-.744c.683-.436 1.327-1.135 1.66-2.316");
}

.w3_s37nup {
  d: path("m12.18 6.524l-.285-.528l.44-.238a.8.8 0 0 1-.019.338a.5.5 0 0 0 .05.357l.276.512c-.028.016-.053.029-.139-.018c-.138-.075-.291-.359-.323-.423");
}

.w5oxhdc5r {
  stop-color: var(--svg-color--7f5d9d, #7F5D9D);
}

.w9zd-yl1d {
  d: path("M11.595 27.789c0-.807.458-1.16.688-1.235l1.367 1.18v1.283a.5.5 0 0 0 .187.39l.203.163c.128.094.297.238.25.414c-.082.172-.25.195-.539.195h-1.506a.65.65 0 0 1-.65-.65z");
}

.wa00b45sw {
  stop-color: var(--svg-color--ffc651, #FFC651);
  stop-opacity: 0;
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.we0trlbug {
  stop-color: var(--svg-color--246c9d, #246C9D);
  stop-opacity: 0;
}

.wn-t5ndzy {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x-1t1ccta {
  cx: 16.383px;
  cy: 5.242px;
  r: 0.415px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.x9_x14ckq {
  stop-color: var(--svg-color--3090bc, #3090BC);
  stop-opacity: 0;
}

.xhu8yhbcw {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
  stop-opacity: 0;
}

.xi8fv135v {
  stop-color: var(--svg-color--8c7e97, #8C7E97);
  stop-opacity: 0;
}

.xqdsusm2m {
  d: path("m16.15 23.554l-.375-5.953l1.062.5v5.453z");
}

.xr-frx4ha {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.216 5.412c.04.019.012.083-.021.155c-.033.071-.059.123-.099.104c-.04-.018-.046-.091-.013-.163c.033-.071.093-.114.133-.096");
}

.y6ovumr8k {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
}

.ybwhezbaj {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.253 7.34a1.3 1.3 0 0 1-.574.154c-.065.002-.088.088-.032.116c.224.12.506.129.75-.003a.79.79 0 0 0 .414-.626c.006-.064-.078-.09-.114-.037a1.25 1.25 0 0 1-.444.396Z");
}

.ydllxhbat {
  stop-color: var(--svg-color--4195cb, #4195CB);
  stop-opacity: 0;
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.ynlfw99ba {
  stop-color: var(--svg-color--403451, #403451);
}

.yrm14tb3b {
  stop-color: var(--svg-color--579fde, #579FDE);
  stop-opacity: 0;
}

.yzcwl7btv {
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("m19.822 16.617l-.188 11.187");
}

.z1w_hpbnu {
  d: path("M15.202 5.33a.372.372 0 0 1 .54.243l-.633.343a.374.374 0 0 1 .093-.586");
}

.z7_c_lb_j {
  cx: 16.383px;
  cy: 5.242px;
  r: 0.698px;
}

.z71hdhjff {
  fill: var(--svg-color--afa2b8, #AFA2B8);
  d: path("M8.948 12.89a.35.35 0 0 0-.125.474l.88 1.545a1 1 0 0 1-.373 1.364l-.115.065a1 1 0 0 1-1.364-.374l-.728-1.277a1.65 1.65 0 0 1 .617-2.25l.343-.196l16.303-9.709a.4.4 0 0 1 .549.14l.102.171a.4.4 0 0 1-.14.549z");
}

.zglchomad {
  fill: var(--svg-color--4c3765, #4C3765);
  d: path("M18.177 30.18v-1.77h2.16c.164.156.79.55 1.504.78c.494.132.625.49.63.622v.367z");
}

.zjm96qmni {
  stop-color: var(--svg-color--d47e31, #D47E31);
  stop-opacity: 0;
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zn47ozbfv {
  stop-color: var(--svg-color--442563, #442563);
  stop-opacity: 0;
}

.zymwyoupt {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.467 6.139a.58.58 0 0 0-.287.658c.018.073.1.108.166.072l.82-.443a.096.096 0 0 0 .03-.145a.585.585 0 0 0-.729-.142");
}

</style>
