<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i0RtVte)" transform="rotate(39.16 14.713 7.657)" class="yheiuhpmg"/><path fill="url(#iTjhCRb)" class="gac8n8bcn"/><g filter="url(#iPAhdod)"><path fill="url(#icJZ7Mb)" class="xh27eqbwx"/><path fill="url(#iiB44Bd)" class="xh27eqbwx"/><path fill="url(#iuCIBpd)" class="xh27eqbwx"/></g><path clip-rule="evenodd" class="v2cxwe7iu"/><g filter="url(#i5AsHIr)"><path clip-rule="evenodd" class="b8q008d8y"/></g><g filter="url(#iSUMtqB)"><path fill="url(#i1hByyb)" class="n1sk6gblf"/><path fill="url(#i45ojle)" class="n1sk6gblf"/></g><path fill="url(#iJ27ZmA)" class="s-k6hrbic"/><g filter="url(#iSfR17b)"><path class="i2hze-b1r"/><path fill="url(#iT3eYJc)" class="auj-xkbur"/></g><path fill="url(#iLqY6mW)" class="cc5062bsq"/><path fill="url(#iUVtrkb)" class="s3iyeh_3a"/><path fill="url(#iGMQD6c)" class="s3iyeh_3a"/><path fill="url(#irdjZbd)" class="s3iyeh_3a"/><path fill="url(#ifs5xpc)" class="s3iyeh_3a"/><g filter="url(#iVannTd)"><path fill="url(#iIaJJ8d)" class="by1exjb7f"/><path fill="url(#iB3N3Xd)" class="by1exjb7f"/><path fill="url(#iOgwese)" class="by1exjb7f"/></g><g filter="url(#iRJM98b)"><rect fill="url(#iovWBvb)" class="ymrjn_brj"/><rect fill="url(#i4FKieb)" class="ymrjn_brj"/><rect fill="url(#i099wVd)" class="ymrjn_brj"/><rect fill="url(#iySv6Ne)" class="ymrjn_brj"/></g><rect fill="url(#iNchOLb)" transform="rotate(-21.787 19.331 12.99)" class="v9tcgeb6g"/><path fill="url(#iOheOtc)" class="rpitvbc7v"/><path fill="url(#iWFfxnE)" class="rpitvbc7v"/><path fill="url(#i29DNkb)" class="rpitvbc7v"/><g filter="url(#iFxC1Xd)"><path fill="url(#iiJGgjb)" class="ubd4yp-3v"/></g><g filter="url(#iGAFFFc)"><path fill="url(#i1Jdwmd)" class="ur3uusblv"/><path fill="url(#ilvc4Kd)" class="ur3uusblv"/><path fill="url(#i2csXfe)" class="ur3uusblv"/></g><g filter="url(#iGXilEe)"><path class="uradqgbmx"/><path fill="url(#iQ220Jd)" class="w7fu92buk"/></g><g filter="url(#i4HFnHe)"><path stroke="url(#iECrTPd)" class="jmjqn3afv"/></g><g filter="url(#i31PSad)"><path fill="url(#i24Hh4d)" class="cwk9srbga"/></g><path class="ph9lhbc6u"/><path fill="url(#iecVJJb)" class="j6v94qbyl"/><path fill="url(#iJIbc1b)" class="hfef972qs"/><path class="k7e_vkb_u"/><g filter="url(#ilDTdac)"><path class="k5wptsb7t"/></g><defs><radialGradient id="i0RtVte" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.332 9.632)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="eml4kgi9k"/><stop offset="1" class="h5h4umnpl"/></radialGradient><radialGradient id="iTjhCRb" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.279 10.498)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="nt8xhhbat"/><stop offset="1" class="tyyfqbc6n"/></radialGradient><radialGradient id="icJZ7Mb" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.176 5.254)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="hm38bnbpu"/><stop offset="1" class="wxw4scccx"/></radialGradient><radialGradient id="iiB44Bd" cx="0" cy="0" r="1" gradientTransform="matrix(-.1836 .58984 -.6149 -.19139 17.34 7.56)" gradientUnits="userSpaceOnUse"><stop class="so3lhcy0s"/><stop offset="1" class="flid1wbse"/></radialGradient><radialGradient id="iuCIBpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60106 2 -1.01904 -.30625 16.903 6.052)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="lwhkutxfi"/><stop offset="1" class="hi76xjbam"/></radialGradient><radialGradient id="i1hByyb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 1.21872 -1.0591 -3.63905 18.363 5.634)" gradientUnits="userSpaceOnUse"><stop class="pquvpov8y"/><stop offset=".768" class="tbsziibgm"/></radialGradient><radialGradient id="i45ojle" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.53125 1.3125 0 14.685 6.99)" gradientUnits="userSpaceOnUse"><stop class="net2vpb0k"/><stop offset="1" class="nqxolnbbl"/></radialGradient><radialGradient id="iJ27ZmA" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 -.1328 .22485 -.63488 15.855 6.884)" gradientUnits="userSpaceOnUse"><stop class="k10stfbid"/><stop offset="1" class="yauo1s9_t"/></radialGradient><radialGradient id="iT3eYJc" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.016 15.217)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="cpjrx4bdc"/><stop offset="1" class="gezrebbgs"/></radialGradient><radialGradient id="iLqY6mW" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -48.945 48.63)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="irdjZbd" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 21.978)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="ifs5xpc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 21.884)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="iIaJJ8d" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.23 15.067)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="iB3N3Xd" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.882 10.383)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="iOgwese" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.072)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="i4FKieb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.103)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="i099wVd" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.574)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="iySv6Ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -9.78125 0 17.957 16.353)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="iNchOLb" cx="0" cy="0" r="1" gradientTransform="matrix(.6797 -.01657 .00353 .14487 19.826 13.25)" gradientUnits="userSpaceOnUse"><stop class="zvi39h0vi"/><stop offset="1" class="y8vzjr5cn"/></radialGradient><radialGradient id="iOheOtc" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.323 10.746)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="iiJGgjb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 20.916)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="ilvc4Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 28.884)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="iQ220Jd" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.29687 .16254 .33364 20.747 13.864)" gradientUnits="userSpaceOnUse"><stop class="bj1143m9c"/><stop offset="1" class="y32gqkb3q"/></radialGradient><radialGradient id="i24Hh4d" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.103)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="r_erdlb4g"/><stop offset="1" class="w1kjbmbah"/></radialGradient><radialGradient id="iecVJJb" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .539 .14228 17.542 7.714)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="k23k8xbao"/><stop offset="1" class="cemcwib4u"/></radialGradient><radialGradient id="iJIbc1b" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.448)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><filter id="iPAhdod" width="4.364" height="4.439" x="14.22" y="5.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.498039 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23073"/></filter><filter id="i5AsHIr" width=".763" height=".367" x="17.253" y="6.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.301961 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23073"/></filter><filter id="iSUMtqB" width="5.022" height="4.224" x="13.841" y="3.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.729412 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23073"/></filter><filter id="iSfR17b" width="6.377" height="6.141" x="9.574" y="8.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.478431 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.466667 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23073" result="effect2_innerShadow_3987_23073"/></filter><filter id="iVannTd" width="27.983" height="6.037" x="2.059" y="20.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23073"/></filter><filter id="iRJM98b" width="24.059" height="2.191" x="3.886" y="15.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23073"/></filter><filter id="iFxC1Xd" width="6.802" height="6.803" x="8.337" y="19.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23073"/></filter><filter id="iGAFFFc" width="27.983" height="6.037" x="1.959" y="23.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23073"/></filter><filter id="iGXilEe" width="6.678" height="4.108" x="14.785" y="10.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.537255 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23073"/></filter><filter id="i4HFnHe" width="5.181" height="3.008" x="14.85" y="11.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23073" stdDeviation=".2"/></filter><filter id="i31PSad" width="3.882" height="3.705" x="12.803" y="9.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.25098 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23073"/></filter><filter id="ilDTdac" width="3.316" height="1.688" x="15.443" y="4.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23073" stdDeviation=".125"/></filter><linearGradient id="iUVtrkb" x1="25.051" x2="7.801" y1="18.822" y2="24.197" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="iGMQD6c" x1="27.145" x2="26.441" y1="20.384" y2="20.384" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="iovWBvb" x1="16.015" x2="16.395" y1="15.228" y2="18.759" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="iWFfxnE" x1="17.168" x2="17.582" y1="16.263" y2="16.658" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="i29DNkb" x1="19.52" x2="19.184" y1="15.947" y2="15.595" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="i1Jdwmd" x1="18.457" x2="12.738" y1="23.353" y2="33.447" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="i2csXfe" x1="18.02" x2="18.02" y1="29.916" y2="29.634" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient><linearGradient id="iECrTPd" x1="15.778" x2="20.06" y1="12.208" y2="13.927" gradientUnits="userSpaceOnUse"><stop class="o5cz0x_yz"/><stop offset="1" class="uwp25_jkx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-rowing-boat-medium-light" /></template>
<style>
.a_bfjubwy {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
  stop-opacity: 0;
}

.a-c1axuni {
  stop-color: var(--svg-color--679951, #679951);
}

.afnbbr78b {
  stop-color: var(--svg-color--5fcdff, #5FCDFF);
}

.akun2bbyl {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
}

.auj-xkbur {
  d: path("M11.168 10.525c-1.006 1.231-1.414 2.668-1.594 3.274l3.992 1.25c.125-1.024.75-2.72 1.172-3.375c.422-.657.489-.872.555-1.348s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.b8q008d8y {
  fill: var(--svg-color--9e6b41, #9E6B41);
  fill-rule: evenodd;
  d: path("M17.874 6.779a.72.72 0 0 0-.488-.028a.1.1 0 0 1-.066-.189a.92.92 0 0 1 .637.035a.1.1 0 0 1-.084.182");
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bj1143m9c {
  stop-color: var(--svg-color--e8bea3, #E8BEA3);
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.by1exjb7f {
  d: path("M3.504 20.9c-.775-.425-1.254-.422-1.445-.422v5.938H29.94v-5.938c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.cc5062bsq {
  d: path("M9.598 13.681c-.243.895-.203 1.762-.11 2.024l6.309-.063z");
}

.cemcwib4u {
  stop-color: var(--svg-color--a38c84, #A38C84);
}

.cpjrx4bdc {
  stop-color: var(--svg-color--e03932, #E03932);
}

.cwk9srbga {
  d: path("M13.004 11.025c.6.719 1.333 1.555 1.625 1.883l1.656-1.484c-.33-.396-1.117-1.304-1.617-1.766c-.625-.578-1.27-.191-1.469 0c-.172.166-.672.687-.195 1.367");
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

.eml4kgi9k {
  stop-color: var(--svg-color--bf7966, #BF7966);
}

.espuh9d_f {
  stop-color: var(--svg-color--8d8695, #8D8695);
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

.gac8n8bcn {
  d: path("M18.232 8.013c-.081-.147-.066-.411-.047-.504l-.445 1.02c.14.074.378.14.515-.031c.098-.121.079-.301-.023-.485");
}

.gezrebbgs {
  stop-color: var(--svg-color--e03932, #E03932);
  stop-opacity: 0;
}

.h5h4umnpl {
  stop-color: var(--svg-color--da9076, #DA9076);
}

.hfef972qs {
  d: path("M17.641 7.733q.045-.05.061-.11c.027-.098-.019-.205-.097-.227c-.08-.02-.17.04-.198.148a.3.3 0 0 0-.002.126z");
}

.hi76xjbam {
  stop-color: var(--svg-color--eeb597, #EEB597);
  stop-opacity: 0;
}

.hm38bnbpu {
  stop-color: var(--svg-color--efbb9e, #EFBB9E);
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.i2hze-b1r {
  fill: var(--svg-color--fa623e, #FA623E);
  d: path("M11.168 10.525c-1.006 1.231-1.414 2.668-1.594 3.274l3.992 1.25c.125-1.024.75-2.72 1.172-3.375c.422-.657.489-.872.555-1.348s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.j6v94qbyl {
  d: path("M17.72 7.755c.02-.037.038-.064.051-.113c.048-.177-.02-.354-.169-.394c-.138-.037-.296.08-.343.257a.5.5 0 0 0-.012.123z");
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.jmjqn3afv {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.403 11.677c.292.349.89.87 1.805 1.164c1.438.46 1.734.515 2.36.726");
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.k10stfbid {
  stop-color: var(--svg-color--ecb497, #ECB497);
}

.k23k8xbao {
  stop-color: var(--svg-color--6b4841, #6B4841);
}

.k5wptsb7t {
  fill: var(--svg-color--fff2bc, #FFF2BC);
  d: path("M17.068 5.99c-.675-.138-1.198.187-1.375.366c.632-1 1.43-.656 2.054-.68c.5-.018.709-.346.75-.507c.006.172.064.53-.144.715c-.256.227-.442.277-1.285.105");
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.k7e_vkb_u {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.362c.016-.036.07-.048.119-.026s.075.07.059.106c-.017.037-.07.049-.119.027s-.075-.07-.059-.107");
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

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.n1sk6gblf {
  d: path("M13.872 7.519c.085-.194.296-.227.39-.219c-.39-.766-.085-2.687.65-3.047a1.77 1.77 0 0 1 1.577.024c.243.132.567.445 1.27.41c.645-.033 1 .332 1.004.691c.004.36-.117.844-.637.961s-.758-.07-1.394-.148c-.492-.06-.866.277-.989.468c-.183.29-.615.915-.75 1.137c-.168.277-.406.402-.73.34c-.324-.063-.496-.375-.39-.617");
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

.ph9lhbc6u {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.735c.048.012.099-.027.124-.083l.003-.01c.066-.247-.096-.438-.295-.49c-.189-.052-.434.03-.5.277l-.003.01c-.015.059.01.118.066.133z");
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

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.r_erdlb4g {
  stop-color: var(--svg-color--ff9954, #FF9954);
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.rpitvbc7v {
  d: path("M21.334 12.23a.59.59 0 0 1 .829.84l-8.439 8.33a.59.59 0 1 1-.829-.839z");
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.s-k6hrbic {
  d: path("M15.919 6.527a.625.625 0 0 0-.373 1.175z");
}

.s3iyeh_3a {
  d: path("m5.232 16.937l21.725-.021v6.25l-18.008-.117z");
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
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

.ubd4yp-3v {
  d: path("M11.366 20.279a1.917 1.917 0 1 1 2.712 2.71l-2.468 2.47a1.917 1.917 0 1 1-2.712-2.711z");
}

.ur3uusblv {
  d: path("M3.504 24.4c-.775-.425-1.254-.422-1.445-.422v5.938H29.94v-5.938c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.uradqgbmx {
  fill: var(--svg-color--e0b492, #E0B492);
  d: path("M16.504 13.736c-.713-.331-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.279 2.684 1.352c.395.094 1.538.3 2.168.73c.516.352.379.993.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.719");
}

.uwp25_jkx {
  stop-color: var(--svg-color--e8b79d, #E8B79D);
  stop-opacity: 0;
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v2cxwe7iu {
  fill: var(--svg-color--880f4d, #880F4D);
  fill-rule: evenodd;
  d: path("M16.98 8.422a.1.1 0 0 1 .132.05c.032.07.15.243.339.325a.1.1 0 0 1-.079.183a.92.92 0 0 1-.442-.425a.1.1 0 0 1 .05-.133");
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
}

.v9tcgeb6g {
  width: 1.28px;
  height: 0.637px;
  x: 19.331px;
  y: 12.99px;
  rx: 0.318px;
}

.w1kjbmbah {
  stop-color: var(--svg-color--f9663c, #F9663C);
}

.w7fu92buk {
  d: path("M16.504 13.736c-.713-.331-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.279 2.684 1.352c.395.094 1.538.3 2.168.73c.516.352.379.993.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.719");
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

.xh27eqbwx {
  d: path("M15.931 9.618c-.914-.453-1.535-1.234-1.71-1.617l.662-1.593a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.008.263-.002.372.067c.288.183.576.644.369 1.476c-.229 1.08-.501 1.743-.749 2.226c-.177.345-.533.572-.916.506a3.2 3.2 0 0 1-.718-.217");
}

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.y32gqkb3q {
  stop-color: var(--svg-color--e8bea3, #E8BEA3);
  stop-opacity: 0;
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

.yheiuhpmg {
  d: path("M14.713 7.657h1.744v2h-1.744z");
}

.ymrjn_brj {
  width: 23.859px;
  height: 2.191px;
  x: 4.086px;
  y: 15.479px;
  rx: 1.095px;
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

.zvi39h0vi {
  stop-color: var(--svg-color--d1a587, #D1A587);
}

</style>
