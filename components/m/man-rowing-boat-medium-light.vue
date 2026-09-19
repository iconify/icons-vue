<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iYAsRKe)" transform="rotate(39.16 14.713 7.881)" class="jv1tt0l5n"/><path fill="url(#iIT0qzu)" class="y0mlfnbzg"/><g filter="url(#iU1LDXd)"><path fill="url(#iTblXDb)" class="jy8-i5b8m"/><path fill="url(#iXBDSAb)" class="jy8-i5b8m"/><path fill="url(#iQooKWc)" class="jy8-i5b8m"/></g><path clip-rule="evenodd" class="iqcdozbzt"/><g filter="url(#i6Yuytb)"><path clip-rule="evenodd" class="elm3h5byl"/></g><g filter="url(#iNJlNCc)"><path fill="url(#i3kFX8c)" class="ioz2fx6gq"/><path fill="url(#iKg9I3c)" class="ioz2fx6gq"/></g><path fill="url(#i4CixUb)" class="bk-cajbee"/><g filter="url(#iyJnrzd)"><path class="gie5m-9bw"/><path fill="url(#isV4t1d)" class="jywlxbb4q"/></g><path fill="url(#iNVbeJb)" class="u75ffgbuj"/><path fill="url(#ifoythc)" class="c_97ke8vt"/><path fill="url(#iBZmdXd)" class="c_97ke8vt"/><path fill="url(#ioNmvAc)" class="c_97ke8vt"/><path fill="url(#iwzsG7T)" class="c_97ke8vt"/><g filter="url(#iymfWKe)"><path fill="url(#iTluQ8m)" class="cyc_rmm_f"/><path fill="url(#iYAYzjd)" class="cyc_rmm_f"/><path fill="url(#iF5Cygc)" class="cyc_rmm_f"/></g><g filter="url(#iblOEwb)"><rect fill="url(#ii2Dmlc)" class="fz50xwb5q"/><rect fill="url(#iVUM4vd)" class="fz50xwb5q"/><rect fill="url(#idq2p1b)" class="fz50xwb5q"/><rect fill="url(#ipRzb7b)" class="fz50xwb5q"/></g><rect fill="url(#ikT2zrV)" transform="rotate(-21.787 19.523 13.24)" class="qubw24nxk"/><path fill="url(#i0IpWAe)" class="mud6gxbyq"/><path fill="url(#itP7qSd)" class="mud6gxbyq"/><path fill="url(#i1rujWc)" class="mud6gxbyq"/><g filter="url(#iMhzxsb)"><path fill="url(#iiw2GHr)" class="y65r12fpx"/></g><g filter="url(#i3fhAwb)"><path fill="url(#iY3lQFd)" class="b_tmv-bwn"/><path fill="url(#i4qwnmW)" class="b_tmv-bwn"/><path fill="url(#ijwta8d)" class="b_tmv-bwn"/></g><g filter="url(#ipITIdY)"><path class="hm05y3b4v"/><path fill="url(#iaFwMCc)" class="zwlaz3fft"/></g><g filter="url(#iRykT5c)"><path stroke="url(#iSqhkGd)" class="zl_ub_fsl"/></g><g filter="url(#idoR1lc)"><path fill="url(#iAQQOad)" class="ab2zcacrn"/></g><path class="slpmyab8b"/><path fill="url(#io5VY4d)" class="yz8f1j3rx"/><path fill="url(#i2YJi4c)" class="ewpayk28h"/><path class="cu9t5ozxp"/><defs><radialGradient id="iYAsRKe" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.258 9.744)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="zavz50bxt"/><stop offset="1" class="q265kokej"/></radialGradient><radialGradient id="iIT0qzu" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.2 10.61)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="nt8xhhbat"/><stop offset="1" class="tyyfqbc6n"/></radialGradient><radialGradient id="iTblXDb" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.158 5.366)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="hm38bnbpu"/><stop offset="1" class="wxw4scccx"/></radialGradient><radialGradient id="iXBDSAb" cx="0" cy="0" r="1" gradientTransform="rotate(107.289 5.806 10.274)scale(.61776 .64399)" gradientUnits="userSpaceOnUse"><stop class="so3lhcy0s"/><stop offset="1" class="flid1wbse"/></radialGradient><radialGradient id="iQooKWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.60106 2 -1.01904 -.30625 16.903 6.276)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="lwhkutxfi"/><stop offset="1" class="hi76xjbam"/></radialGradient><radialGradient id="i3kFX8c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.31333 1.068 -.80702 -3.2593 18.613 5.864)" gradientUnits="userSpaceOnUse"><stop class="pquvpov8y"/><stop offset=".768" class="tbsziibgm"/></radialGradient><radialGradient id="iKg9I3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.09453 1.35194 0 14.823 7.051)" gradientUnits="userSpaceOnUse"><stop class="net2vpb0k"/><stop offset="1" class="nqxolnbbl"/></radialGradient><radialGradient id="i4CixUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 -.1328 .22485 -.63488 15.855 7.108)" gradientUnits="userSpaceOnUse"><stop class="k10stfbid"/><stop offset="1" class="yauo1s9_t"/></radialGradient><radialGradient id="isV4t1d" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.168 15.329)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="ynstgccdl"/><stop offset="1" class="ph7rypboq"/></radialGradient><radialGradient id="iNVbeJb" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -49.789 48.742)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="ioNmvAc" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 22.202)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="iwzsG7T" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 22.108)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="iTluQ8m" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.182 15.179)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="iYAYzjd" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.93 10.494)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="iF5Cygc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.296)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="iVUM4vd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.327)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="idq2p1b" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.798)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="ipRzb7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -9.78125 0 17.957 16.577)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="ikT2zrV" cx="0" cy="0" r="1" gradientTransform="matrix(.6797 -.01657 .00353 .14487 20.018 13.5)" gradientUnits="userSpaceOnUse"><stop class="zvi39h0vi"/><stop offset="1" class="y8vzjr5cn"/></radialGradient><radialGradient id="i0IpWAe" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.277 10.858)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="iiw2GHr" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 21.14)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="i4qwnmW" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 29.108)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="iaFwMCc" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.29687 .16254 .33364 20.747 14.088)" gradientUnits="userSpaceOnUse"><stop class="bj1143m9c"/><stop offset="1" class="y32gqkb3q"/></radialGradient><radialGradient id="iAQQOad" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.327)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="v0g3nqbgo"/><stop offset="1" class="mcj2tdbkt"/></radialGradient><radialGradient id="io5VY4d" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .539 .14228 17.543 7.936)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="k23k8xbao"/><stop offset="1" class="cemcwib4u"/></radialGradient><radialGradient id="i2YJi4c" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.67)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><filter id="iU1LDXd" width="4.17" height="4.439" x="14.414" y="5.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.505882 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23075"/></filter><filter id="i6Yuytb" width=".763" height=".367" x="17.245" y="6.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.301961 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23075"/></filter><filter id="iNJlNCc" width="5.17" height="3.72" x="13.955" y="4.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.729412 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23075"/></filter><filter id="iyJnrzd" width="6.377" height="6.141" x="9.574" y="9.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.447059 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23075"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.447059 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23075" result="effect2_innerShadow_3987_23075"/></filter><filter id="iymfWKe" width="27.983" height="6.037" x="2.059" y="20.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23075"/></filter><filter id="iblOEwb" width="24.059" height="2.191" x="3.886" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23075"/></filter><filter id="iMhzxsb" width="6.802" height="6.803" x="8.337" y="19.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23075"/></filter><filter id="i3fhAwb" width="27.983" height="6.037" x="1.959" y="24.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23075"/></filter><filter id="ipITIdY" width="6.678" height="4.108" x="14.785" y="11.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.592157 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23075"/></filter><filter id="iRykT5c" width="5.181" height="3.008" x="14.805" y="11.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23075" stdDeviation=".2"/></filter><filter id="idoR1lc" width="3.882" height="3.705" x="12.803" y="9.427" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.392157 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23075"/></filter><linearGradient id="ifoythc" x1="25.051" x2="7.801" y1="19.046" y2="24.421" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="iBZmdXd" x1="27.145" x2="26.441" y1="20.608" y2="20.608" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="ii2Dmlc" x1="16.015" x2="16.395" y1="15.452" y2="18.983" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="itP7qSd" x1="17.168" x2="17.582" y1="16.487" y2="16.882" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="i1rujWc" x1="19.52" x2="19.184" y1="16.171" y2="15.819" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="iY3lQFd" x1="18.457" x2="12.738" y1="23.577" y2="33.671" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="ijwta8d" x1="18.02" x2="18.02" y1="30.14" y2="29.858" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient><linearGradient id="iSqhkGd" x1="15.734" x2="20.015" y1="12.432" y2="14.151" gradientUnits="userSpaceOnUse"><stop class="o5cz0x_yz"/><stop offset="1" class="uwp25_jkx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-rowing-boat-medium-light" /></template>
<style>
.a_bfjubwy {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
  stop-opacity: 0;
}

.a-c1axuni {
  stop-color: var(--svg-color--679951, #679951);
}

.ab2zcacrn {
  d: path("M13.004 11.249c.6.719 1.333 1.555 1.625 1.883l1.656-1.485c-.33-.395-1.117-1.303-1.617-1.765c-.625-.578-1.27-.192-1.469 0c-.172.165-.672.687-.195 1.367");
}

.afnbbr78b {
  stop-color: var(--svg-color--5fcdff, #5FCDFF);
}

.akun2bbyl {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
}

.b_tmv-bwn {
  d: path("M3.504 24.624c-.775-.425-1.254-.422-1.445-.422v5.938H29.94v-5.938c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bj1143m9c {
  stop-color: var(--svg-color--e8bea3, #E8BEA3);
}

.bk-cajbee {
  d: path("M15.919 6.751a.625.625 0 0 0-.373 1.175z");
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.c_97ke8vt {
  d: path("m5.232 17.161l21.725-.021v6.25l-18.008-.118z");
}

.cemcwib4u {
  stop-color: var(--svg-color--a38c84, #A38C84);
}

.cu9t5ozxp {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.586c.016-.036.07-.048.119-.026s.075.07.059.106c-.017.037-.07.048-.119.026s-.075-.07-.059-.106");
}

.cyc_rmm_f {
  d: path("M3.504 21.124c-.775-.425-1.254-.422-1.445-.422v5.938H29.94v-5.938c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
}

.dzuixsuao {
  stop-color: var(--svg-color--55beff, #55BEFF);
  stop-opacity: 0;
}

.e_s-6on8g {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
  stop-opacity: 0;
}

.e21-2rm4b {
  stop-color: var(--svg-color--659941, #659941);
}

.elm3h5byl {
  fill: var(--svg-color--9e6b41, #9E6B41);
  fill-rule: evenodd;
  d: path("M17.866 7.125a.72.72 0 0 0-.488-.028a.1.1 0 0 1-.066-.189a.92.92 0 0 1 .637.035a.1.1 0 1 1-.083.182");
}

.espuh9d_f {
  stop-color: var(--svg-color--8d8695, #8D8695);
}

.ewpayk28h {
  d: path("M17.641 7.957q.045-.05.061-.11c.027-.099-.019-.206-.097-.227c-.08-.02-.17.04-.198.148a.3.3 0 0 0-.002.126z");
}

.f3ogmdbgo {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
}

.f6scwccnd {
  stop-color: var(--svg-color--4d8c4e, #4D8C4E);
}

.flid1wbse {
  stop-color: var(--svg-color--f2c2a3, #F2C2A3);
  stop-opacity: 0;
}

.fsljb8bqi {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fz50xwb5q {
  width: 23.859px;
  height: 2.191px;
  x: 4.086px;
  y: 15.703px;
  rx: 1.095px;
}

.gie5m-9bw {
  fill: var(--svg-color--338ae5, #338AE5);
  d: path("M11.168 10.749c-1.006 1.231-1.414 2.668-1.594 3.273l3.992 1.25c.125-1.023.75-2.718 1.172-3.375c.422-.656.489-.87.555-1.347s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.hi76xjbam {
  stop-color: var(--svg-color--eeb597, #EEB597);
  stop-opacity: 0;
}

.hm05y3b4v {
  fill: var(--svg-color--e6b694, #E6B694);
  d: path("M16.504 13.96c-.713-.331-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.279 2.684 1.352c.395.094 1.538.3 2.168.73c.516.352.379.992.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.72");
}

.hm38bnbpu {
  stop-color: var(--svg-color--efbb9e, #EFBB9E);
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.ioz2fx6gq {
  d: path("M13.992 7.433c-.16-1.207.231-2.071.46-2.417a.98.98 0 0 1 .867-.516c.324-.004.493.168.75.121c.103-.019.474-.156.77.027c.246.153.445.235.605.235c.227 0 .557-.044.797.3c.25.36.543.333.695.575s.137.773-.277.968c-.414.196-1.313-.21-1.641-.343s-.55-.075-.752.246c-.163.256-.462.311-.592.316c-.093.193-.307.696-.61.992c-.322.317-1 .035-1.072-.504");
}

.iqcdozbzt {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M16.98 8.646a.1.1 0 0 1 .132.05c.032.07.15.243.339.324a.1.1 0 0 1-.079.184a.92.92 0 0 1-.442-.425a.1.1 0 0 1 .05-.133");
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jv1tt0l5n {
  d: path("M14.713 7.881h1.744v2h-1.744z");
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.jy8-i5b8m {
  d: path("M15.931 9.842a4.2 4.2 0 0 1-1.203-.91c-.38-.408-.386-1-.172-1.514l.327-.786a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.008.263-.002.372.067c.288.182.576.644.369 1.476c-.229 1.08-.501 1.743-.749 2.226c-.177.344-.533.572-.916.506a3.2 3.2 0 0 1-.718-.217");
}

.jywlxbb4q {
  d: path("M11.168 10.749c-1.006 1.231-1.414 2.668-1.594 3.273l3.992 1.25c.125-1.023.75-2.718 1.172-3.375c.422-.656.489-.87.555-1.347s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.k10stfbid {
  stop-color: var(--svg-color--ecb497, #ECB497);
}

.k23k8xbao {
  stop-color: var(--svg-color--6b4841, #6B4841);
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.lwhkutxfi {
  stop-color: var(--svg-color--eeb597, #EEB597);
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.mcj2tdbkt {
  stop-color: var(--svg-color--397bd7, #397BD7);
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.mud6gxbyq {
  d: path("M21.334 12.454a.59.59 0 0 1 .829.84l-8.439 8.331a.59.59 0 1 1-.829-.84z");
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.net2vpb0k {
  stop-color: var(--svg-color--fae0b7, #FAE0B7);
}

.nqxolnbbl {
  stop-color: var(--svg-color--fae0b7, #FAE0B7);
  stop-opacity: 0;
}

.nt8xhhbat {
  stop-color: var(--svg-color--e2b496, #E2B496);
}

.o5cz0x_yz {
  stop-color: var(--svg-color--e8b79d, #E8B79D);
}

.ph7rypboq {
  stop-color: var(--svg-color--275dc4, #275DC4);
  stop-opacity: 0;
}

.pjzjl2c9v {
  stop-color: var(--svg-color--59a0ff, #59A0FF);
}

.pna-0uy1p {
  stop-color: var(--svg-color--cd9157, #CD9157);
}

.pquvpov8y {
  stop-color: var(--svg-color--fff8ba, #FFF8BA);
}

.q265kokej {
  stop-color: var(--svg-color--b77f62, #B77F62);
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.qubw24nxk {
  width: 1.28px;
  height: 0.637px;
  x: 19.523px;
  y: 13.239px;
  rx: 0.318px;
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
}

.slpmyab8b {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.958c.048.013.099-.026.124-.083l.003-.01c.066-.246-.096-.437-.295-.49c-.189-.05-.434.031-.5.278l-.003.01c-.015.059.01.118.066.133z");
}

.so3lhcy0s {
  stop-color: var(--svg-color--f2c2a3, #F2C2A3);
}

.tbsziibgm {
  stop-color: var(--svg-color--ffe0a6, #FFE0A6);
}

.tyyfqbc6n {
  stop-color: var(--svg-color--d29e83, #D29E83);
}

.u75ffgbuj {
  d: path("M9.598 13.905c-.243.895-.203 1.762-.11 2.024l6.309-.063z");
}

.uwp25_jkx {
  stop-color: var(--svg-color--e8b79d, #E8B79D);
  stop-opacity: 0;
}

.v0g3nqbgo {
  stop-color: var(--svg-color--579ff0, #579FF0);
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
}

.wqxg4jbgc {
  stop-color: var(--svg-color--286ec5, #286EC5);
  stop-opacity: 0;
}

.wvez-gyvu {
  stop-color: var(--svg-color--86bf45, #86BF45);
}

.wwotuurhh {
  stop-color: var(--svg-color--528c3f, #528C3F);
  stop-opacity: 0;
}

.wxw4scccx {
  stop-color: var(--svg-color--e29f87, #E29F87);
}

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.y0mlfnbzg {
  d: path("M18.232 8.237c-.081-.147-.066-.411-.047-.504l-.445 1.02c.14.074.378.14.515-.031c.098-.121.079-.301-.023-.485");
}

.y32gqkb3q {
  stop-color: var(--svg-color--e8bea3, #E8BEA3);
  stop-opacity: 0;
}

.y65r12fpx {
  d: path("M11.366 20.503a1.917 1.917 0 0 1 2.712 2.71l-2.468 2.47a1.917 1.917 0 0 1-2.712-2.711z");
}

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.y8vzjr5cn {
  stop-color: var(--svg-color--c89b7b, #C89B7B);
}

.yauo1s9_t {
  stop-color: var(--svg-color--e4a589, #E4A589);
}

.ynstgccdl {
  stop-color: var(--svg-color--275dc4, #275DC4);
}

.yz8f1j3rx {
  d: path("M17.72 7.979c.02-.037.038-.064.051-.113c.048-.178-.02-.354-.169-.394c-.138-.037-.296.08-.343.257a.5.5 0 0 0-.012.123z");
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.zavz50bxt {
  stop-color: var(--svg-color--a4744f, #A4744F);
}

.zl_ub_fsl {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.359 11.9c.291.35.889.871 1.804 1.165c1.438.46 1.735.515 2.36.726");
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

.zvi39h0vi {
  stop-color: var(--svg-color--d1a587, #D1A587);
}

.zwlaz3fft {
  d: path("M16.504 13.96c-.713-.331-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.279 2.684 1.352c.395.094 1.538.3 2.168.73c.516.352.379.992.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.72");
}

</style>
