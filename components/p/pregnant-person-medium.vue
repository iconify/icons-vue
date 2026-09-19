<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iPuKChP)"><path class="vu5c7zbtr"/><path fill="url(#iTEEJed)" class="awfnklbvn"/><path fill="url(#ipU49te)" class="awfnklbvn"/><path fill="url(#irHDnSG)" class="awfnklbvn"/><path fill="url(#itOwDae)" class="awfnklbvn"/></g><g filter="url(#iN0jIZH)"><path class="ubdk6gbjo"/></g><g filter="url(#iQ9DVtd)"><path fill="url(#iaxbbod)" class="azb4cuehx"/><path fill="url(#ijO7qZb)" class="azb4cuehx"/><path fill="url(#irvuq6c)" class="azb4cuehx"/></g><g filter="url(#i9BIxDe)"><path fill="url(#iKfwVOb)" class="lgvovmjhd"/><path fill="url(#ixynhbc)" class="lgvovmjhd"/></g><g filter="url(#iOilW9y)"><path stroke="url(#i3JinDd)" class="jsy133bpu"/></g><g filter="url(#iYd3XAe)"><path stroke="url(#i9WRkIc)" class="aod4o2bzp"/></g><g filter="url(#iTF74Pd)"><path stroke="url(#i4EUX1c)" class="mtaekvbud"/></g><g filter="url(#itQKIke)"><path stroke="url(#iYRC8nd)" class="ig1mf6bdv"/></g><path fill="url(#itSuMxe)" class="peqbd6bts"/><path fill="url(#iewzWGq)" class="xz4gq0blm"/><g filter="url(#iLkdkpV)"><path fill="url(#ibYMzqd)" class="p-z_nuswl"/><path fill="url(#iy1RtJb)" class="p-z_nuswl"/></g><path fill="url(#iYE3ndd)" class="p-z_nuswl"/><path fill="url(#i2GJnZa)" class="p-z_nuswl"/><path fill="url(#ia0JZKe)" class="p-z_nuswl"/><path fill="url(#iFmUeKe)" class="p-z_nuswl"/><path fill="url(#iiz5G5d)" class="p-z_nuswl"/><path fill="url(#igzXVTb)" class="p-z_nuswl"/><path fill="url(#ivtm9pF)" class="p-z_nuswl"/><path fill="url(#iFNJiqd)" class="p-z_nuswl"/><g filter="url(#iGKG6Pe)"><path class="qfp5cwb8s"/></g><g filter="url(#i6rtxFc)"><path class="gbkxdpbpb"/><path fill="url(#iMMU0Fe)" class="e_qw1qbxq"/><path fill="url(#i7mdF9b)" class="e_qw1qbxq"/><path fill="url(#idTFiQd)" class="e_qw1qbxq"/><path fill="url(#izhsUFd)" class="e_qw1qbxq"/><path fill="url(#iQMmLkC)" class="e_qw1qbxq"/></g><path fill="url(#i5namVb)" class="e_qw1qbxq"/><path fill="url(#iLBonke)" class="e_qw1qbxq"/><g filter="url(#iCR0ecd)"><path stroke="url(#iyrcTii)" class="gbwjv4btc"/></g><path fill="url(#iNP8V2d)" class="kjauadb2r"/><g filter="url(#ivnFurE)"><path fill="url(#iloaL9c)" class="f17ye2zaq"/></g><path fill="url(#iTv1xJD)" class="f17ye2zaq"/><path fill="url(#iopP1Ub)" class="f17ye2zaq"/><path fill="url(#iN0XZGc)" class="f17ye2zaq"/><g filter="url(#i3h95Vd)"><path class="n2tjz-dgn"/></g><g filter="url(#i39NrBd)"><path class="jrk1czbic"/></g><g filter="url(#iRHNjjb)"><path class="o19r4w9wk"/><path fill="url(#iAs2TSc)" class="eti38tb4f"/><path fill="url(#icm5lab)" class="eti38tb4f"/></g><g filter="url(#ii77XDn)"><path class="rgz7kyb3n"/><path fill="url(#iyGRasd)" class="tlx-abrjl"/><path fill="url(#iAn5Xae)" class="tlx-abrjl"/><path fill="url(#iZ8gbfc)" class="tlx-abrjl"/></g><path class="rtmimyt9l"/><path fill="url(#i20gAgJ)" class="wg8sfgbhz"/><path class="zw2o3obso"/><g filter="url(#iKZxT4c)"><path class="s_v56pl9y"/><path fill="url(#icBIMAe)" class="fg_ya3bza"/></g><g filter="url(#iggwgdd)"><path fill="url(#iBrXtjd)" class="rqybbo00b"/></g><path class="u1829zfzs"/><path fill="url(#ifBtoje)" class="ifzn6rblk"/><path class="xr3rxwhpo"/><g filter="url(#iTG8LHd)"><path fill="url(#ilOL7xe)" class="tusg0wblt"/></g><g filter="url(#iLfdJOb)"><ellipse transform="rotate(-27.914 16.313 8.706)" class="q8hp53rqc"/><ellipse fill="url(#iU07Jic)" transform="rotate(-27.914 16.313 8.706)" class="r4d5zy_tt"/></g><path fill="url(#i1rGWHd)" class="xk5ac7b4n"/><path fill="url(#iLTXoBc)" class="xk5ac7b4n"/><path fill="url(#iuczMhd)" class="xk5ac7b4n"/><path fill="url(#i0juHRb)" class="xk5ac7b4n"/><path fill="url(#imRyDrb)" class="rxx5zxsmn"/><path fill="url(#ioTTuRb)" class="rxx5zxsmn"/><g filter="url(#irpuHcM)"><path fill="url(#i1iaBEc)" class="t5zuagnbt"/></g><g filter="url(#iYxwhfj)"><path fill="url(#iwdtged)" class="jbzy5jbdp"/></g><g filter="url(#iQ30bjc)"><path class="h53_bx45s"/></g><g filter="url(#iaEyFuf)"><path class="zxvq-ibsu"/></g><g filter="url(#ivwlyrc)"><path class="zrjy9zxyk"/></g><defs><radialGradient id="iTEEJed" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.2441 14.467 0 14.97 29.685)" gradientUnits="userSpaceOnUse"><stop class="i0nsp7bni"/><stop offset="1" class="j9mdirbao"/></radialGradient><radialGradient id="ipU49te" cx="0" cy="0" r="1" gradientTransform="matrix(-.36327 -1.99342 2.97247 -.54169 20.997 15.747)" gradientUnits="userSpaceOnUse"><stop class="y8skcxtgz"/><stop offset="1" class="j0n9-bc_s"/></radialGradient><radialGradient id="irHDnSG" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.0625 -2.6875 0 20.634 21.722)" gradientUnits="userSpaceOnUse"><stop class="le_3nbbjw"/><stop offset="1" class="imi34--zw"/></radialGradient><radialGradient id="itOwDae" cx="0" cy="0" r="1" gradientTransform="matrix(-6.39747 2.14876 -.75252 -2.24047 18.813 13.573)" gradientUnits="userSpaceOnUse"><stop offset=".449" class="vp7op3b3o"/><stop offset="1" class="akwhn1mys"/></radialGradient><radialGradient id="iKfwVOb" cx="0" cy="0" r="1" gradientTransform="rotate(115.321 5.939 15.46)scale(4.28183 3.28478)" gradientUnits="userSpaceOnUse"><stop offset=".425" class="l863e7bwo"/><stop offset="1" class="h-d21x52g"/></radialGradient><radialGradient id="ixynhbc" cx="0" cy="0" r="1" gradientTransform="rotate(118.72 6.288 14.772)scale(2.6272 1.65249)" gradientUnits="userSpaceOnUse"><stop class="xhl3qijdh"/><stop offset="1" class="phlxv6bym"/></radialGradient><radialGradient id="itSuMxe" cx="0" cy="0" r="1" gradientTransform="matrix(.66382 1.7904 -2.12687 .78857 22.702 10.438)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iewzWGq" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -28.868 48.184)scale(1.37207 4.23294)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="ibYMzqd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.17122 0 0 -7.37885 20.977 9.603)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iy1RtJb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.54539 2.55587 -2.11008 -1.27585 20.64 5.189)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="i2GJnZa" cx="0" cy="0" r="1" gradientTransform="matrix(-.90625 11.01398 -9.1209 -.75048 19.89 4.36)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="ia0JZKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.01806 1.25985 0 20.657 8.44)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iFmUeKe" cx="0" cy="0" r="1" gradientTransform="matrix(.00348 -.97013 1.05572 .0038 16.448 8.48)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iiz5G5d" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 10.6 5.579)scale(7.54706 19.2789)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="igzXVTb" cx="0" cy="0" r="1" gradientTransform="matrix(3.00165 -2.58558 .76374 .88664 12.467 7.18)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="ivtm9pF" cx="0" cy="0" r="1" gradientTransform="matrix(-.20803 2.21409 -.88506 -.08316 23.403 7.017)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iFNJiqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7727 -1.48337 0 16.523 9.164)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="i7mdF9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2164 -.68014 0 18.901 10.809)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="izhsUFd" cx="0" cy="0" r="1" gradientTransform="rotate(156.092 8.411 7.164)scale(1.64088 2.63702)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iLBonke" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 7.423 8.803)scale(1.57128 2.26774)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iNP8V2d" cx="0" cy="0" r="1" gradientTransform="matrix(1.93443 -.95102 3.82618 7.78268 18.053 12.815)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iTv1xJD" cx="0" cy="0" r="1" gradientTransform="matrix(2.42972 -6.3384 8.99413 3.44775 13.428 7.897)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iopP1Ub" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 14.917 -5.37)scale(5.96428 8.46325)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iN0XZGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0036 -2.1128 2.4942 -1.18476 21.35 4.147)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iAs2TSc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9514 0 0 -.72424 18.713 3.227)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="icm5lab" cx="0" cy="0" r="1" gradientTransform="matrix(2.85308 -4.51732 5.00472 3.16092 13.673 6.722)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iyGRasd" cx="0" cy="0" r="1" gradientTransform="rotate(-38.837 17.886 -25.888)scale(4.00084 6.20043)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="iAn5Xae" cx="0" cy="0" r="1" gradientTransform="matrix(2.62316 -2.34776 4.29814 4.80234 20.823 6.609)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="iZ8gbfc" cx="0" cy="0" r="1" gradientTransform="matrix(2.85935 .64197 -.26878 1.19716 20.057 4.994)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="i20gAgJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71927 -1.14408 0 20.422 8.79)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="icBIMAe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.281 -.519)scale(.33537 .46172)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ifBtoje" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7193 -1.14414 0 16.553 8.79)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iU07Jic" cx="0" cy="0" r="1" gradientTransform="matrix(-.00686 -.43803 .52653 -.00824 16.3 8.985)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLTXoBc" cx="0" cy="0" r="1" gradientTransform="matrix(.55724 1.98876 -1.89744 .53165 22.582 8.803)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iuczMhd" cx="0" cy="0" r="1" gradientTransform="matrix(.6984 -.95844 .80337 .5854 22.901 9.286)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="i0juHRb" cx="0" cy="0" r="1" gradientTransform="matrix(.5204 -1.37452 1.83655 .69533 23.002 9.439)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="ioTTuRb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47011 0 0 -1.64159 14.13 9.371)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="i1iaBEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 .13945 -.14298 -.83307 14.13 9.374)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><filter id="iPuKChP" width="16.1" height="17.295" x="7.545" y="12.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737772 0 0 0 0 0.308243 0 0 0 0 0.219096 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4528"/></filter><filter id="iN0jIZH" width="15.69" height="15.109" x="7.228" y="14.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".5"/></filter><filter id="iQ9DVtd" width="16.543" height="14.071" x="6.157" y="15.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.411765 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4528"/></filter><filter id="i9BIxDe" width="4.451" height="5.283" x="18.446" y="15.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.262745 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4528"/></filter><filter id="iOilW9y" width="1.542" height=".3" x="6.796" y="26.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".05"/></filter><filter id="iYd3XAe" width="1.542" height=".3" x="6.429" y="27.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".05"/></filter><filter id="iTF74Pd" width="1.542" height=".3" x="6.617" y="28.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".05"/></filter><filter id="itQKIke" width="12.538" height="9.787" x="8.325" y="19.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".4"/></filter><filter id="iLkdkpV" width="10.061" height="11.041" x="13.999" y="4.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4528"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_4528" result="effect2_innerShadow_13929_4528"/></filter><filter id="iGKG6Pe" width="3.549" height="4.571" x="16.588" y="7.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".5"/></filter><filter id="i6rtxFc" width="2.064" height="2.971" x="17.456" y="8.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".1"/></filter><filter id="iCR0ecd" width="3.353" height="1.451" x="16.811" y="11.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".05"/></filter><filter id="ivnFurE" width="11.412" height="7.465" x="12.782" y="1.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4528"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_4528" result="effect2_innerShadow_13929_4528"/></filter><filter id="i3h95Vd" width="2.085" height="1.078" x="19.897" y="6.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4528"/></filter><filter id="i39NrBd" width="2.085" height="1.065" x="15.237" y="6.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4528"/></filter><filter id="iRHNjjb" width="5.894" height="5.369" x="13.069" y="2.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4528"/><feGaussianBlur result="effect2_foregroundBlur_13929_4528" stdDeviation=".125"/></filter><filter id="ii77XDn" width="6.414" height="5.36" x="18.351" y="2.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4528"/><feGaussianBlur result="effect2_foregroundBlur_13929_4528" stdDeviation=".125"/></filter><filter id="iKZxT4c" width=".72" height=".64" x="19.76" y="8.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".05"/></filter><filter id="iggwgdd" width=".836" height=".855" x="20.493" y="8.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".1"/></filter><filter id="iTG8LHd" width=".92" height=".967" x="16.555" y="8.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".1"/></filter><filter id="iLfdJOb" width=".832" height=".647" x="15.897" y="8.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".05"/></filter><filter id="irpuHcM" width="1.235" height="2.166" x="13.069" y="8.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".125"/></filter><filter id="iYxwhfj" width="1.714" height="2.559" x="22.465" y="8.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".25"/></filter><filter id="iQ30bjc" width="2.217" height="1.114" x="15.122" y="6.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".125"/></filter><filter id="iaEyFuf" width="2.217" height="1.114" x="19.835" y="6.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".125"/></filter><filter id="ivwlyrc" width="4.928" height="2.871" x="19.304" y="2.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4528" stdDeviation=".375"/></filter><linearGradient id="iaxbbod" x1="20.071" x2="7.415" y1="20.785" y2="30.566" gradientUnits="userSpaceOnUse"><stop class="mp4f6nbba"/><stop offset="1" class="z1hfp9biq"/></linearGradient><linearGradient id="ijO7qZb" x1="6.415" x2="9.04" y1="27.66" y2="27.472" gradientUnits="userSpaceOnUse"><stop class="i2qx85vxl"/><stop offset="1" class="h-m8uue-h"/></linearGradient><linearGradient id="irvuq6c" x1="19.727" x2="18.79" y1="18.691" y2="20.504" gradientUnits="userSpaceOnUse"><stop class="jqlv09cqm"/><stop offset="1" class="t-ddqlbvh"/></linearGradient><linearGradient id="i3JinDd" x1="6.946" x2="8.399" y1="26.551" y2="26.551" gradientUnits="userSpaceOnUse"><stop class="wfflv5fdg"/><stop offset="1" class="dpx-tpb3y"/></linearGradient><linearGradient id="i9WRkIc" x1="6.579" x2="8.032" y1="27.488" y2="27.488" gradientUnits="userSpaceOnUse"><stop class="wfflv5fdg"/><stop offset="1" class="dpx-tpb3y"/></linearGradient><linearGradient id="i4EUX1c" x1="6.767" x2="8.22" y1="28.387" y2="28.387" gradientUnits="userSpaceOnUse"><stop class="wfflv5fdg"/><stop offset="1" class="dpx-tpb3y"/></linearGradient><linearGradient id="iYRC8nd" x1="19.969" x2="6.781" y1="20.605" y2="29.136" gradientUnits="userSpaceOnUse"><stop class="blmgsbc5b"/><stop offset="1" class="z43dy1qxy"/></linearGradient><linearGradient id="iYE3ndd" x1="23.06" x2="20.818" y1="11.097" y2="11.097" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iMMU0Fe" x1="19.231" x2="18.488" y1="10.201" y2="10.232" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="idTFiQd" x1="18.488" x2="18.488" y1="11.211" y2="10.799" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iQMmLkC" x1="18.488" x2="18.488" y1="8.813" y2="9.297" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="i5namVb" x1="18.857" x2="18.857" y1="11.333" y2="11.162" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="iyrcTii" x1="17.423" x2="17.705" y1="12.604" y2="11.864" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iloaL9c" x1="24.563" x2="14.268" y1="4.583" y2="4.583" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iBrXtjd" x1="21.112" x2="20.834" y1="8.838" y2="9.01" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilOL7xe" x1="17.213" x2="16.935" y1="8.838" y2="9.01" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1rGWHd" x1="24.194" x2="23.124" y1="8.862" y2="10.792" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="imRyDrb" x1="13.302" x2="14.595" y1="9.486" y2="9.373" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iwdtged" x1="23.322" x2="23.322" y1="8.588" y2="10.147" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pregnant-person-medium" /></template>
<style>
.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.akwhn1mys {
  stop-color: var(--svg-color--ee3404, #EE3404);
  stop-opacity: 0;
}

.aod4o2bzp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M6.58 27.488h1.24");
}

.awfnklbvn {
  d: path("M16.856 12.48c-2.205.676-3.886 3.247-3.886 5.61v.716a.53.53 0 0 1-.407.504c-2.869.705-5.018 3.106-5.018 6.148v1.215c0 1.657 1.345 3 3.004 3l10.163.012c.968 0 1.684-.783 1.684-1.75V15.702c0-1.296-.846-2.238-2.038-2.487c-.154-.033-.308-.063-.462-.099a3.5 3.5 0 0 1-.763-.256l-.059-.03c-.694-.346-1.476-.577-2.218-.35");
}

.azb4cuehx {
  d: path("M21.69 15.529a1.676 1.676 0 0 1 .872 2.202c-.383.886-1.065 2.411-1.961 3.979c-.879 1.537-2.043 3.259-3.434 4.433c-2.342 1.976-4.764 2.698-6.745 2.923c-.929.129-2.169.232-3.109.184c-.457-.024-.735-.232-.785-.477a.5.5 0 0 1 .062-.366a.526.526 0 0 1-.177-.9a.525.525 0 0 1 .27-.976h.18a.504.504 0 0 1 .243-.945h1.098a1.6 1.6 0 0 1-.258-.43c-.1-.237.024-.507.253-.623c.237-.12.522-.04.692.164c.598.713 1.248 1.044 1.79.947c1.352-.24 2.917-.805 4.351-2.015c.935-.79 1.84-2.144 2.66-3.581c.804-1.407 1.428-2.799 1.795-3.647a1.675 1.675 0 0 1 2.202-.872");
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
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

.blmgsbc5b {
  stop-color: var(--svg-color--b5877e, #B5877E);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dpx-tpb3y {
  stop-color: var(--svg-color--85624e, #85624E);
  stop-opacity: 0;
}

.e_qw1qbxq {
  d: path("m18.149 8.969l-.471 1.63c-.096.335.134.67.461.67h.698c.326 0 .557-.34.461-.67l-.471-1.63c-.101-.361-.572-.361-.678 0");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eti38tb4f {
  d: path("M18.694 4.624a2 2 0 0 1-.059-.121a.59.59 0 0 0-.545-.371h-1.13c-1.635 0-2.96 1.34-2.96 2.996v.244c-.301-.23-.68-.714-.68-1.497c0-.95.693-1.43 1.135-1.737c.124-.086.23-.159.293-.224l.088-.093c.31-.329.862-.914 1.826-1.17a4.8 4.8 0 0 1 1.245-.148c.473.003.807.412.807.885v1.224z");
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.f17ye2zaq {
  d: path("M22.792 3.714c.456.157.865.475 1.124.932a2.1 2.1 0 0 1-.094 2.24c-.155.228-.24.499-.24.774v1.054a1.55 1.55 0 0 0-.592-.238l.07-1.424a1.285 1.285 0 0 0-1.223-1.27h-1.241c-.846 0-1.613-.5-1.96-1.279a.59.59 0 0 0-.546-.37h-1.13C15.325 4.132 14 5.472 14 7.127l.027 1.363c-.225.033-.46.108-.638.233V7.66c0-.275-.085-.546-.24-.775a2.12 2.12 0 0 1-.127-2.168c.259-.49.677-.832 1.152-.999c.508-.18.94-.523 1.227-.984a2.06 2.06 0 0 1 2.563-.808c.338.147.72.147 1.058 0c.25-.105.522-.167.809-.167c.747 0 1.4.404 1.763 1.004c.273.451.7.78 1.199.95");
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fg_ya3bza {
  d: path("M20.366 8.535c.056.075-.061.167-.195.267s-.234.171-.29.096s.006-.218.14-.318s.289-.12.345-.045");
}

.ft5dv1b6b {
  fill: none;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
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

.gbkxdpbpb {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m18.149 8.969l-.471 1.63c-.096.335.134.67.461.67h.698c.326 0 .557-.34.461-.67l-.471-1.63c-.101-.361-.572-.361-.678 0");
}

.gbwjv4btc {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.295 11.813c.344.18.755.283 1.193.283c.443 0 .85-.104 1.194-.283a.21.21 0 0 1 .25.04c.06.063.082.163.022.253m-2.66-.293l2.598.252m-2.597-.252h-.001a.21.21 0 0 0-.25.043a.196.196 0 0 0-.022.25m.273-.293l-.21.252m2.87.041l-.063-.041m.062.041l-.062-.041m.062.041c-.31.47-.85.784-1.466.784a1.75 1.75 0 0 1-1.466-.783m2.87-.042a1.68 1.68 0 0 1-1.404.75c-.59 0-1.107-.3-1.404-.75m-.062.042l.062-.042m-.062.042l.062-.042");
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

.h-d21x52g {
  stop-color: var(--svg-color--ec541d, #EC541D);
}

.h-m8uue-h {
  stop-color: var(--svg-color--9c7568, #9C7568);
  stop-opacity: 0;
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.h53_bx45s {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.497 7.113a2.05 2.05 0 0 1 1.468-.338");
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

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i0nsp7bni {
  stop-color: var(--svg-color--d7454a, #D7454A);
}

.i2qx85vxl {
  stop-color: var(--svg-color--9c7568, #9C7568);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ifzn6rblk {
  d: path("M16.552 8.368a.79.79 0 0 0-.763 1h1.529a.797.797 0 0 0-.766-1");
}

.ig1mf6bdv {
  stroke-linecap: round;
  d: path("M19.563 20.355c-1.042 2.063-4.488 6.387-9.938 7.188");
}

.imi34--zw {
  stop-color: var(--svg-color--ff7634, #FF7634);
  stop-opacity: 0;
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j0n9-bc_s {
  stop-color: var(--svg-color--ff7a45, #FF7A45);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j9mdirbao {
  stop-color: var(--svg-color--fc5428, #FC5428);
  stop-opacity: 0;
}

.jbzy5jbdp {
  d: path("M22.965 10.147q.044-.78.084-1.559c.355.049.63.378.63.777c0 .43-.319.778-.714.782");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jqlv09cqm {
  stop-color: var(--svg-color--916865, #916865);
}

.jrk1czbic {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M15.464 6.864a2.46 2.46 0 0 1 1.542-.319a.246.246 0 1 1-.06.489a1.97 1.97 0 0 0-1.23.252q-.045.028-.066.043l-.015.01l-.002.002a.246.246 0 0 1-.301-.389z");
}

.jsy133bpu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M6.946 26.55h1.242");
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.kjauadb2r {
  d: path("M18.488 12.17c-.45 0-.873-.105-1.228-.29c-.122-.062-.252.074-.176.185c.297.45.815.75 1.404.75c.59 0 1.107-.3 1.404-.75c.076-.115-.054-.247-.176-.185a2.65 2.65 0 0 1-1.228.29");
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l863e7bwo {
  stop-color: var(--svg-color--ff6420, #FF6420);
}

.le_3nbbjw {
  stop-color: var(--svg-color--ff7634, #FF7634);
}

.lgvovmjhd {
  d: path("M22.665 18.062c.39-1.09-.127-2.166-.976-2.533a1.675 1.675 0 0 0-2.202.872c-.266.616-.533 1.241-1.04 2.228l3.046 1.945c.567-1.099.924-1.82 1.172-2.512");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mp4f6nbba {
  stop-color: var(--svg-color--b3867d, #B3867D);
}

.mtaekvbud {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M6.767 28.387h1.242");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n2tjz-dgn {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M21.797 6.961a1.6 1.6 0 0 0-.61-.365c-.269-.085-.607-.107-1.074-.05a.246.246 0 1 0 .06.488c.426-.052.687-.025.867.031c.176.056.295.145.434.267a.246.246 0 0 0 .323-.371");
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o19r4w9wk {
  fill: var(--svg-color--533634, #533634);
  d: path("M18.694 4.624a2 2 0 0 1-.059-.121a.59.59 0 0 0-.545-.371h-1.13c-1.635 0-2.96 1.34-2.96 2.996v.244c-.301-.23-.68-.714-.68-1.497c0-.95.693-1.43 1.135-1.737c.124-.086.23-.159.293-.224l.088-.093c.31-.329.862-.914 1.826-1.17a4.8 4.8 0 0 1 1.245-.148c.473.003.807.412.807.885v1.224z");
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p-z_nuswl {
  d: path("M14.21 12.054a3.47 3.47 0 0 0 3.445 3.02h1.673a3.47 3.47 0 0 0 3.445-3.02c.104-1.67.21-3.333.287-5.002a1.285 1.285 0 0 0-1.223-1.27h-1.241a2.15 2.15 0 0 1-1.96-1.279a.59.59 0 0 0-.546-.37h-1.13C15.325 4.132 14 5.472 14 7.127c0 1.65.103 3.272.211 4.926");
}

.peqbd6bts {
  d: path("M22.798 10.711c.297-.01.575-.11.802-.274v.826c0 .792-.472 1.497-1.19 1.79q.229-.484.308-1.046z");
}

.phlxv6bym {
  stop-color: var(--svg-color--ff5d1d, #FF5D1D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q8hp53rqc {
  cx: 16.313px;
  cy: 8.706px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.345px;
  ry: 0.175px;
}

.qfp5cwb8s {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m18.132 9.143l-.524 1.63c-.09.335.125.67.43.67h.648c.305 0 .52-.34.43-.67l-.439-1.63c-.094-.361-.447-.361-.545 0");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r4d5zy_tt {
  cx: 16.313px;
  cy: 8.706px;
  rx: 0.345px;
  ry: 0.175px;
}

.rgz7kyb3n {
  fill: var(--svg-color--563936, #563936);
  d: path("m23.109 7.52l-.026-.56c-.01-.676-.569-1.235-1.246-1.263h-1.241c-.788 0-1.507-.43-1.883-1.117c0 0-.02-.048-.05-.135c-.316-.952.625-1.708 1.607-1.5c.813.172 1.705.454 2.377.893c1.547 1.008 1.276 2.826.462 3.682");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rqybbo00b {
  d: path("M21.129 9.055a.75.75 0 0 0-.205-.41l-.23.252l.103.203z");
}

.rtmimyt9l {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.608 8.126c.579 0 1.068.4 1.2.94a.243.243 0 0 1-.236.301h-1.979a.204.204 0 0 1-.2-.24c.11-.569.61-1 1.215-1");
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.rxx5zxsmn {
  d: path("M14.016 7.95a1.44 1.44 0 0 0-1.234 1.417c0 .762.597 1.384 1.348 1.425a69 69 0 0 1-.114-2.841");
}

.s_v56pl9y {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.366 8.535c.056.075-.061.167-.195.267s-.234.171-.29.096s.006-.218.14-.318s.289-.12.345-.045");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.t-ddqlbvh {
  stop-color: var(--svg-color--916865, #916865);
  stop-opacity: 0;
}

.t5zuagnbt {
  d: path("M13.98 8.54a.847.847 0 0 0 .073 1.667q-.046-.833-.074-1.666");
}

.tlx-abrjl {
  d: path("m23.109 7.52l-.026-.56c-.01-.676-.569-1.235-1.246-1.263h-1.241c-.788 0-1.507-.43-1.883-1.117c0 0-.02-.048-.05-.135c-.316-.952.625-1.708 1.607-1.5c.813.172 1.705.454 2.377.893c1.547 1.008 1.276 2.826.462 3.682");
}

.tusg0wblt {
  d: path("M17.275 9.066c0-.256-.208-.426-.265-.478l-.255.248l.157.32z");
}

.u1829zfzs {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.368 8.126c-.579 0-1.068.4-1.2.94a.242.242 0 0 0 .237.301h1.978a.204.204 0 0 0 .201-.24c-.111-.569-.615-1-1.216-1");
}

.ubdk6gbjo {
  fill: var(--svg-color--e23405, #E23405);
  d: path("M10.47 28.719q.229-.028.44-.06c1.886-.224 3.507-.32 5.738-2.297c1.325-1.174 2.434-2.896 3.27-4.433c.854-1.568 1.503-3.093 1.868-3.98c.35-.849-.022-1.834-.83-2.202c-.81-.367-1.749.024-2.098.873c-.35.848-.944 2.24-1.71 3.646c-.782 1.437-1.644 2.793-2.534 3.581a8.56 8.56 0 0 1-4.145 2.016c-.516.096-1.135-.235-1.704-.947a.56.56 0 0 0-.494-.216a7 7 0 0 0-.043.759v1.214c0 1.164 1.318 1.548 2.241 2.046");
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vp7op3b3o {
  stop-color: var(--svg-color--ee3404, #EE3404);
}

.vu5c7zbtr {
  fill: var(--svg-color--ff6428, #FF6428);
  d: path("M16.856 12.48c-2.205.676-3.886 3.247-3.886 5.61v.716a.53.53 0 0 1-.407.504c-2.869.705-5.018 3.106-5.018 6.148v1.215c0 1.657 1.345 3 3.004 3l10.163.012c.968 0 1.684-.783 1.684-1.75V15.702c0-1.296-.846-2.238-2.038-2.487c-.154-.033-.308-.063-.462-.099a3.5 3.5 0 0 1-.763-.256l-.059-.03c-.694-.346-1.476-.577-2.218-.35");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wfflv5fdg {
  stop-color: var(--svg-color--85624e, #85624E);
}

.wg8sfgbhz {
  d: path("M20.424 8.368a.79.79 0 0 1 .763 1h-1.529a.794.794 0 0 1 .766-1");
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.xhl3qijdh {
  stop-color: var(--svg-color--ff8147, #FF8147);
}

.xk5ac7b4n {
  d: path("M22.851 10.792q.09-1.415.164-2.83a1.427 1.427 0 0 1-.164 2.83");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xr3rxwhpo {
  fill: var(--svg-color--000, #000);
  d: path("M17.005 9.159a.45.45 0 0 0-.453-.453a.45.45 0 0 0-.403.661h.802a.45.45 0 0 0 .054-.208");
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.xz4gq0blm {
  d: path("M14.178 10.711a1.45 1.45 0 0 1-.802-.274v.826c0 .792.472 1.497 1.189 1.79a3.6 3.6 0 0 1-.307-1.046z");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y8skcxtgz {
  stop-color: var(--svg-color--ff7a45, #FF7A45);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.z1hfp9biq {
  stop-color: var(--svg-color--a87b70, #A87B70);
}

.z43dy1qxy {
  stop-color: var(--svg-color--b5877e, #B5877E);
  stop-opacity: 0;
}

.zrjy9zxyk {
  fill: var(--svg-color--725050, #725050);
  d: path("M22.388 4.627h-1.895a.44.44 0 1 1 .07-.875c.492.078 1.145.188 1.582.296c.988.245 1.26.726 1.337 1.07a1.38 1.38 0 0 0-1.094-.491");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

.zw2o3obso {
  fill: var(--svg-color--000, #000);
  d: path("M19.97 9.159c0-.252.202-.453.454-.453a.45.45 0 0 1 .403.661h-.802a.4.4 0 0 1-.054-.208");
}

.zxvq-ibsu {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M21.678 7.063c-.228-.163-.796-.45-1.468-.338");
}

</style>
