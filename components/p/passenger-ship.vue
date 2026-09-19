<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ibLomMd)"><path fill="url(#ih0HwLd)" class="n6p1pd-eq"/></g><path fill="url(#idpRinb)" class="s3v_ivvgo"/><path class="ot-y7wq-c"/><path fill="url(#icCcqxd)" class="s3v_ivvgo"/><path fill="url(#iQYl5cc)" class="si84k8zfk"/><path class="be8-f3ngs"/><path fill="url(#ilnhXUd)" class="si84k8zfk"/><path fill="url(#iaG1rXc)" class="w6cmpacxx"/><path class="ld5g0gw8s"/><path fill="url(#iCzY9Jd)" class="w6cmpacxx"/><path fill="url(#iu8th5d)" class="w6cmpacxx"/><path class="hk26xzbrw"/><path fill="url(#i1s4xAr)" class="rc006x1oc"/><path fill="url(#ibogzqc)" class="rc006x1oc"/><path fill="url(#iYiZKSc)" class="lbuljwb8u"/><path class="pz6xn3-ii"/><path fill="url(#ioT9sHe)" class="h7a3gsbhh"/><path class="c49c-vbxx"/><path fill="url(#ijhPfrd)" class="pm6rwue5v"/><path fill="url(#iP9JkHe)" class="v8wq7w5db"/><g filter="url(#iPOmV2v)"><path class="wz8v0db8u"/></g><path fill="url(#i8mDwfe)" class="s7163qo5k"/><path fill="url(#iLaU8KP)" class="jnv6g1dgp"/><path fill="url(#i1YMFhc)" class="flb1p-bor"/><path fill="url(#im0x0Dd)" class="xnavscoaq"/><path fill="url(#iTpsiKd)" class="oorfa8bjh"/><path fill="url(#iBtuZub)" class="ec9jylb4k"/><path fill="url(#iBUA79c)" class="eexbm2bmo"/><path fill="url(#iR5ch6z)" class="h_vcydbbm"/><path fill="url(#irYqAOd)" class="d1t5xcbzu"/><g filter="url(#is5sQtc)"><path class="toyv2dbfr"/></g><g filter="url(#i07dJcU)"><path class="j45lrlbrr"/></g><g filter="url(#ipOtzBe)"><path class="f5pcucbms"/></g><g filter="url(#iA6svwc)"><path class="gn8haispy"/></g><g filter="url(#imbtGkd)"><path class="njsb51msf"/></g><g filter="url(#iOGkRke)"><path class="va695ebbo"/></g><g filter="url(#ic6Og3h)"><path class="q-p9s0f8d"/></g><g filter="url(#iwPB4Pd)"><path class="hhn-drvwe"/></g><g filter="url(#iqRScTc)"><path fill="url(#imyqdLe)" class="dz46j4bnc"/></g><g filter="url(#iJlzapd)"><path class="ooc2yub8y"/></g><g filter="url(#iNlKbJc)"><path class="jp18-zpao"/></g><g filter="url(#iUJGQxb)"><path stroke="url(#iRJVsfe)" class="b42dq-bxv"/></g><defs><linearGradient id="ih0HwLd" x1="27.495" x2="27.495" y1="5" y2="11" gradientUnits="userSpaceOnUse"><stop class="awh9z4bkj"/><stop offset="1" class="t9i9-qfip"/></linearGradient><linearGradient id="idpRinb" x1="11.995" x2="3.763" y1="28.5" y2="20.406" gradientUnits="userSpaceOnUse"><stop offset=".084" class="vc--wpv5i"/><stop offset=".881" class="vc--wpv5i"/><stop offset="1" class="lw79fjbdw"/></linearGradient><linearGradient id="icCcqxd" x1="13.18" x2="14.038" y1="11.62" y2="12.452" gradientUnits="userSpaceOnUse"><stop class="nocwy-b-w"/><stop offset="1" class="qwpkvfb7k"/></linearGradient><linearGradient id="iQYl5cc" x1="9.995" x2=".745" y1="31.5" y2="22.182" gradientUnits="userSpaceOnUse"><stop offset=".084" class="vc--wpv5i"/><stop offset=".881" class="vc--wpv5i"/><stop offset="1" class="lw79fjbdw"/></linearGradient><linearGradient id="ilnhXUd" x1="9.444" x2="10.053" y1="14.62" y2="15.229" gradientUnits="userSpaceOnUse"><stop class="nocwy-b-w"/><stop offset="1" class="qwpkvfb7k"/></linearGradient><linearGradient id="iaG1rXc" x1="25.995" x2="25.867" y1="0" y2="11.091" gradientUnits="userSpaceOnUse"><stop offset=".084" class="vc--wpv5i"/><stop offset=".881" class="vc--wpv5i"/><stop offset="1" class="lw79fjbdw"/></linearGradient><linearGradient id="iCzY9Jd" x1="17.005" x2="17.964" y1="10" y2="10" gradientUnits="userSpaceOnUse"><stop class="okzohmbto"/><stop offset="1" class="as-7wxdfw"/></linearGradient><linearGradient id="iu8th5d" x1="23.995" x2="23.276" y1="10" y2="10" gradientUnits="userSpaceOnUse"><stop class="f73j7ybru"/><stop offset="1" class="te24-10tz"/></linearGradient><linearGradient id="i1s4xAr" x1="20.569" x2="20.569" y1="9.027" y2="8.66" gradientUnits="userSpaceOnUse"><stop class="jtxn3i9nm"/><stop offset="1" class="z_go6wh2n"/></linearGradient><linearGradient id="ibogzqc" x1="20.569" x2="20.569" y1="7.172" y2="8.172" gradientUnits="userSpaceOnUse"><stop class="jtxn3i9nm"/><stop offset="1" class="z_go6wh2n"/></linearGradient><linearGradient id="ioT9sHe" x1="21.498" x2="21.498" y1="11" y2="11.5" gradientUnits="userSpaceOnUse"><stop class="ui_8u6z3l"/><stop offset="1" class="ryme-zv9x"/></linearGradient><linearGradient id="ijhPfrd" x1="19.495" x2="19.495" y1="14" y2="14.5" gradientUnits="userSpaceOnUse"><stop class="ui_8u6z3l"/><stop offset="1" class="ryme-zv9x"/></linearGradient><linearGradient id="i8mDwfe" x1="8.699" x2="29.985" y1="23.503" y2="23.503" gradientUnits="userSpaceOnUse"><stop class="jvnqhab8o"/><stop offset="1" class="xuiiksiqm"/></linearGradient><linearGradient id="iLaU8KP" x1="27.5" x2="27.5" y1="18" y2="20" gradientUnits="userSpaceOnUse"><stop class="j_60945om"/><stop offset="0" class="gds77obnh"/><stop offset=".453" class="re4jribpe"/></linearGradient><linearGradient id="i1YMFhc" x1="25.5" x2="25.5" y1="18" y2="20" gradientUnits="userSpaceOnUse"><stop class="j_60945om"/><stop offset="0" class="gds77obnh"/><stop offset=".453" class="re4jribpe"/></linearGradient><linearGradient id="im0x0Dd" x1="23.5" x2="23.5" y1="18" y2="20" gradientUnits="userSpaceOnUse"><stop class="j_60945om"/><stop offset="0" class="gds77obnh"/><stop offset=".453" class="re4jribpe"/></linearGradient><linearGradient id="iTpsiKd" x1="21.5" x2="21.5" y1="18" y2="20" gradientUnits="userSpaceOnUse"><stop class="j_60945om"/><stop offset="0" class="gds77obnh"/><stop offset=".453" class="re4jribpe"/></linearGradient><linearGradient id="iBtuZub" x1="16.5" x2="16.5" y1="18" y2="20" gradientUnits="userSpaceOnUse"><stop class="j_60945om"/><stop offset="0" class="gds77obnh"/><stop offset=".453" class="re4jribpe"/></linearGradient><linearGradient id="iBUA79c" x1="14.51" x2="14.51" y1="18" y2="20" gradientUnits="userSpaceOnUse"><stop class="j_60945om"/><stop offset="0" class="gds77obnh"/><stop offset=".453" class="re4jribpe"/></linearGradient><linearGradient id="iR5ch6z" x1="12.5" x2="12.5" y1="18" y2="20" gradientUnits="userSpaceOnUse"><stop class="j_60945om"/><stop offset="0" class="gds77obnh"/><stop offset=".453" class="re4jribpe"/></linearGradient><linearGradient id="irYqAOd" x1="10.5" x2="10.5" y1="18" y2="20" gradientUnits="userSpaceOnUse"><stop class="j_60945om"/><stop offset="0" class="gds77obnh"/><stop offset=".453" class="re4jribpe"/></linearGradient><linearGradient id="imyqdLe" x1="10.316" x2="27.619" y1="28.825" y2="28.825" gradientUnits="userSpaceOnUse"><stop class="dmsonjbnm"/><stop offset="1" class="o3_opxbjf"/></linearGradient><linearGradient id="iRJVsfe" x1="8.337" x2="29.437" y1="23.427" y2="23.427" gradientUnits="userSpaceOnUse"><stop class="xcnnfc42m"/><stop offset="1" class="i2l38ib3m"/></linearGradient><filter id="ibLomMd" width="5.4" height="6" x="24.995" y="5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.27451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/></filter><filter id="iPOmV2v" width="28" height="15" x="2.995" y="15.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.537255 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.909804 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12238" result="effect2_innerShadow_18_12238"/></filter><filter id="is5sQtc" width="1.31" height="2.3" x="26.695" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.682353 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/></filter><filter id="i07dJcU" width="1.31" height="2.3" x="24.695" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.682353 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/></filter><filter id="ipOtzBe" width="1.31" height="2.3" x="22.695" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.682353 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/></filter><filter id="iA6svwc" width="1.31" height="2.3" x="20.695" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.682353 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/></filter><filter id="imbtGkd" width="1.31" height="2.3" x="15.695" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.682353 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/></filter><filter id="iOGkRke" width="1.31" height="2.3" x="13.705" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.682353 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/></filter><filter id="ic6Og3h" width="1.31" height="2.3" x="11.695" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.682353 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/></filter><filter id="iwPB4Pd" width="1.31" height="2.3" x="9.695" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.682353 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/></filter><filter id="iqRScTc" width="24.75" height="3.25" x="5.995" y="26.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.231373 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/></filter><filter id="iJlzapd" width="28.61" height="2.92" x="1.395" y="27.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.67451 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 0 0.894118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12238" result="effect2_innerShadow_18_12238"/></filter><filter id="iNlKbJc" width="1.3" height="1.3" x="5.695" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.682353 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12238"/></filter><filter id="iUJGQxb" width="21.818" height="1.05" x="8.144" y="22.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_12238" stdDeviation=".2"/></filter><radialGradient id="iYiZKSc" cx="0" cy="0" r="1" gradientTransform="rotate(134.999 8.981 7.847)scale(.7289)" gradientUnits="userSpaceOnUse"><stop class="edji9obzx"/><stop offset="1" class="bcyn8gbkm"/></radialGradient><radialGradient id="iP9JkHe" cx="0" cy="0" r="1" gradientTransform="rotate(131.634 8.803 11.163)scale(24.0832 17.8669)" gradientUnits="userSpaceOnUse"><stop class="wr7rxybje"/><stop offset=".084" class="vc--wpv5i"/><stop offset=".904" class="vc--wpv5i"/><stop offset=".998" class="sm1teyw2a"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:passenger-ship" /></template>
<style>
.as-7wxdfw {
  stop-color: var(--svg-color--b6b5b7, #B6B5B7);
  stop-opacity: 0;
}

.awh9z4bkj {
  stop-color: var(--svg-color--7d71aa, #7D71AA);
}

.b42dq-bxv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M8.67 23.427h20.767");
}

.bcyn8gbkm {
  stop-color: var(--svg-color--584977, #584977);
}

.be8-f3ngs {
  fill: var(--svg-color--e6deec, #E6DEEC);
  d: path("M11.735 13c-.431 0-.852.17-1.163.47L7.995 16l12 1l10-1v-3z");
}

.c49c-vbxx {
  fill: var(--svg-color--59eaff, #59EAFF);
  d: path("M10.026 14L9 15h20.996v-1z");
}

.d1t5xcbzu {
  d: path("M10.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.dmsonjbnm {
  stop-color: var(--svg-color--69567c, #69567C);
}

.dz46j4bnc {
  d: path("M13.03 30h16.965v-3h-24c1.716 1.818 4.254 3 7.036 3");
}

.ec9jylb4k {
  d: path("M16.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.edji9obzx {
  stop-color: var(--svg-color--8d83b3, #8D83B3);
}

.eexbm2bmo {
  d: path("M14.345 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.f5pcucbms {
  fill: var(--svg-color--5ff3ff, #5FF3FF);
  d: path("M23.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.f73j7ybru {
  stop-color: var(--svg-color--fffdff, #FFFDFF);
}

.flb1p-bor {
  d: path("M25.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.ft5dv1b6b {
  fill: none;
}

.gds77obnh {
  stop-color: var(--svg-color--00a6ed, #00A6ED);
}

.gn8haispy {
  fill: var(--svg-color--5ff3ff, #5FF3FF);
  d: path("M21.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.h_vcydbbm {
  d: path("M12.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.h7a3gsbhh {
  d: path("m13.995 11l-1 1h17.01v-1z");
}

.hhn-drvwe {
  fill: var(--svg-color--5ff3ff, #5FF3FF);
  d: path("M10.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.hk26xzbrw {
  fill: var(--svg-color--6c5d88, #6C5D88);
  d: path("M20.995 7h-1v2h1z");
}

.i2l38ib3m {
  stop-color: var(--svg-color--57515c, #57515C);
}

.j_60945om {
  stop-color: var(--svg-color--7b61ff, #7B61FF);
}

.j45lrlbrr {
  fill: var(--svg-color--5ff3ff, #5FF3FF);
  d: path("M25.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.jnv6g1dgp {
  d: path("M27.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.jp18-zpao {
  fill: var(--svg-color--5ff3ff, #5FF3FF);
  d: path("M5.995 18.5c0 .28.22.5.5.5s.5-.22.5-.5s-.22-.5-.5-.5s-.5.23-.5.5");
}

.jtxn3i9nm {
  stop-color: var(--svg-color--5b477a, #5B477A);
}

.jvnqhab8o {
  stop-color: var(--svg-color--5a3f71, #5A3F71);
}

.lbuljwb8u {
  d: path("M19.745 7.25c0 .412.338.75.75.75s.75-.338.75-.75a.753.753 0 0 0-.75-.75a.753.753 0 0 0-.75.75");
}

.ld5g0gw8s {
  fill: var(--svg-color--ede7f2, #EDE7F2);
  d: path("M17.803 9a.8.8 0 0 0-.798.802V10h6.99v-.198A.8.8 0 0 0 23.197 9z");
}

.lw79fjbdw {
  stop-color: var(--svg-color--9b9b9a, #9B9B9A);
}

.n6p1pd-eq {
  d: path("M28.827 5a2.74 2.74 0 0 0-2.545 1.733L24.995 10l2.5 1l2.5-1V5.634A.63.63 0 0 0 29.361 5z");
}

.njsb51msf {
  fill: var(--svg-color--5ff3ff, #5FF3FF);
  d: path("M16.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.nocwy-b-w {
  stop-color: var(--svg-color--b4b2b4, #B4B2B4);
}

.o3_opxbjf {
  stop-color: var(--svg-color--564e5c, #564E5C);
}

.okzohmbto {
  stop-color: var(--svg-color--b6b5b7, #B6B5B7);
}

.ooc2yub8y {
  fill: var(--svg-color--4f95f5, #4F95F5);
  d: path("M30.005 27.81c-1.75 0-1.76 1.12-3.51 1.12s-1.75-1.12-3.51-1.12c-1.75 0-1.75 1.12-3.5 1.12s-1.75-1.12-3.5-1.12s-1.75 1.12-3.5 1.12s-1.75-1.12-3.5-1.12s-1.75 1.12-3.49 1.12c-1.75 0-1.75-1.12-3.5-1.12v2.32h28.01z");
}

.oorfa8bjh {
  d: path("M21.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.ot-y7wq-c {
  fill: var(--svg-color--e6deec, #E6DEEC);
  d: path("m11.995 13l2.78-2.765a.82.82 0 0 1 .551-.235h14.669v3l-9 1z");
}

.pm6rwue5v {
  d: path("M10.026 14L9 15h20.996v-1z");
}

.pz6xn3-ii {
  fill: var(--svg-color--59eaff, #59EAFF);
  d: path("m13.995 11l-1 1h17.01v-1z");
}

.q-p9s0f8d {
  fill: var(--svg-color--5ff3ff, #5FF3FF);
  d: path("M12.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.qwpkvfb7k {
  stop-color: var(--svg-color--b4b2b4, #B4B2B4);
  stop-opacity: 0;
}

.rc006x1oc {
  d: path("M20.995 7h-1v2h1z");
}

.re4jribpe {
  stop-color: var(--svg-color--26eafc, #26EAFC);
}

.ryme-zv9x {
  stop-color: var(--svg-color--33bdff, #33BDFF);
  stop-opacity: 0;
}

.s3v_ivvgo {
  d: path("m11.995 13l2.78-2.765a.82.82 0 0 1 .551-.235h14.669v3l-9 1z");
}

.s7163qo5k {
  d: path("M8.445 23c-.251 0-.45.22-.45.5s.199.5.45.5h21.55v-1z");
}

.si84k8zfk {
  d: path("M11.735 13c-.431 0-.852.17-1.163.47L7.995 16l12 1l10-1v-3z");
}

.sm1teyw2a {
  stop-color: var(--svg-color--635994, #635994);
}

.t9i9-qfip {
  stop-color: var(--svg-color--65557a, #65557A);
}

.te24-10tz {
  stop-color: var(--svg-color--fffdff, #FFFDFF);
  stop-opacity: 0;
}

.toyv2dbfr {
  fill: var(--svg-color--5ff3ff, #5FF3FF);
  d: path("M27.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.ui_8u6z3l {
  stop-color: var(--svg-color--33bdff, #33BDFF);
}

.v8wq7w5db {
  d: path("M4.582 16c-.962 0-1.711.848-1.57 1.786l.587 4.111c.363 2.067 1.206 3.788 2.396 5.105c.727.804 2.044 1.009 3 1.498c1.345.688 2.426 1.5 4.081 1.5h16.919V16z");
}

.va695ebbo {
  fill: var(--svg-color--5ff3ff, #5FF3FF);
  d: path("M14.345 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w6cmpacxx {
  d: path("M17.803 9a.8.8 0 0 0-.798.802V10h6.99v-.198A.8.8 0 0 0 23.197 9z");
}

.wr7rxybje {
  stop-color: var(--svg-color--d3d2d2, #D3D2D2);
}

.wz8v0db8u {
  fill: var(--svg-color--ddd3e5, #DDD3E5);
  d: path("M4.582 16c-.962 0-1.711.848-1.57 1.786l.587 4.111c.363 2.067 1.206 3.788 2.396 5.105c.727.804 2.044 1.009 3 1.498c1.345.688 2.426 1.5 4.081 1.5h16.919V16z");
}

.xcnnfc42m {
  stop-color: var(--svg-color--6e5c81, #6E5C81);
}

.xnavscoaq {
  d: path("M23.335 18c-.19 0-.34.15-.34.34v1.32c0 .19.15.34.34.34h.33c.19 0 .34-.15.34-.34v-1.32c0-.19-.15-.34-.34-.34z");
}

.xuiiksiqm {
  stop-color: var(--svg-color--43354d, #43354D);
}

.z_go6wh2n {
  stop-color: var(--svg-color--5b477a, #5B477A);
  stop-opacity: 0;
}

</style>
