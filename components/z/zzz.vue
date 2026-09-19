<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="nltn9obzl"/><path stroke="url(#i0vaA5d)" class="folzcdcsp"/><path stroke="url(#idgf9qd)" class="fb97-rokv"/><g filter="url(#iSZJc0d)"><path class="fi_-1x0ja"/></g><path fill="url(#i6jQsKG)" class="ha1-wccoj"/><path fill="url(#iGtNcNd)" class="ha1-wccoj"/><path fill="url(#iqEvYBv)" class="ee-0mbo1l"/><path fill="url(#i7TaFsb)" class="ee-0mbo1l"/><g filter="url(#ifabrdc)"><ellipse transform="rotate(-14.595 9.473 19.227)" class="w7yxd49je"/></g><g filter="url(#iUyf0rd)"><ellipse transform="rotate(18.361 7.993 24.913)" class="cdvqqhbzt"/></g><g filter="url(#ihO7AOc)"><path class="lhv0y9mvb"/></g><path class="jboc_e3pk"/><path stroke="url(#irQ6J1m)" class="pxepw_zdb"/><path fill="url(#iP4ckDc)" class="w6q68ccus"/><path fill="url(#iFPZYDd)" class="w6q68ccus"/><path fill="url(#iO1ubyd)" class="p9_e_gy1n"/><path stroke="url(#iomE58X)" class="k0t3t2b1f"/><path stroke="url(#ig8yNNd)" class="k0t3t2b1f"/><path stroke="url(#imzIrwc)" class="k0t3t2b1f"/><g filter="url(#i4Odjnc)"><ellipse class="h4_a-qv0l"/></g><g filter="url(#i0RutYV)"><ellipse transform="rotate(-38.684 16.914 14.58)" class="n9zlqmbye"/></g><g filter="url(#iYxmeTb)"><path class="gd8-swbym"/></g><path class="gz-ocqbdf"/><path stroke="url(#ieQSVue)" class="zik3cd9jy"/><path stroke="url(#iIY08Dd)" class="zik3cd9jy"/><path fill="url(#icjwfoX)" class="fx494ib8z"/><path fill="url(#iWmza9d)" class="fx494ib8z"/><path fill="url(#iuil5Jb)" class="bzfh-z_gy"/><path fill="url(#ikxvmUc)" class="bzfh-z_gy"/><path fill="url(#ih80zyB)" class="vmsdv5b9s"/><path fill="url(#iydQ1Ic)" clip-rule="evenodd" class="ipst9caif"/><path fill="url(#i9sl0Hb)" class="rrpuvcblk"/><path fill="url(#iZKhjye)" class="rrpuvcblk"/><g filter="url(#iNoHktb)"><ellipse transform="rotate(-15.293 28.64 16)" class="t1m-b_8qj"/></g><g filter="url(#ifw69Ce)"><ellipse transform="rotate(-38.992 25.978 5.515)" class="touikd5wi"/></g><g filter="url(#iVbeBMd)"><path stroke="url(#isG0isd)" class="vfija0yvh"/></g><defs><linearGradient id="idgf9qd" x1="5.007" x2="5.3" y1="25.208" y2="23.631" gradientUnits="userSpaceOnUse"><stop class="kdy_2lb4q"/><stop offset="1" class="labw8tusy"/></linearGradient><linearGradient id="i6jQsKG" x1="6.285" x2="6.746" y1="19.508" y2="17.854" gradientUnits="userSpaceOnUse"><stop class="kdy_2lb4q"/><stop offset="1" class="labw8tusy"/></linearGradient><linearGradient id="iGtNcNd" x1="2.802" x2="4.534" y1="17.945" y2="18.36" gradientUnits="userSpaceOnUse"><stop class="bj6ok_qjs"/><stop offset="1" class="wa36eza7h"/></linearGradient><linearGradient id="iqEvYBv" x1="8.035" x2="6.956" y1="21.648" y2="20.256" gradientUnits="userSpaceOnUse"><stop class="kdy_2lb4q"/><stop offset="1" class="labw8tusy"/></linearGradient><linearGradient id="i7TaFsb" x1="4.113" x2="5.019" y1="20.43" y2="21.57" gradientUnits="userSpaceOnUse"><stop class="bj6ok_qjs"/><stop offset="1" class="wa36eza7h"/></linearGradient><linearGradient id="iP4ckDc" x1="10.628" x2="11.613" y1="19.102" y2="19.945" gradientUnits="userSpaceOnUse"><stop class="n95_0b18g"/><stop offset="1" class="whgjlv6nh"/></linearGradient><linearGradient id="iFPZYDd" x1="13.738" x2="11.957" y1="21.727" y2="20.258" gradientUnits="userSpaceOnUse"><stop class="cerjmceuw"/><stop offset=".705" class="whgjlv6nh"/></linearGradient><linearGradient id="iO1ubyd" x1="11.925" x2="11.925" y1="16.695" y2="14.948" gradientUnits="userSpaceOnUse"><stop class="v3dlubcaj"/><stop offset=".966" class="whgjlv6nh"/></linearGradient><linearGradient id="imzIrwc" x1="13.181" x2="13.181" y1="24.211" y2="22.305" gradientUnits="userSpaceOnUse"><stop offset=".063" class="fxx7_5beg"/><stop offset="1" class="whgjlv6nh"/></linearGradient><linearGradient id="icjwfoX" x1="21.488" x2="20.925" y1="9.32" y2="7.002" gradientUnits="userSpaceOnUse"><stop class="xx9nt_bnq"/><stop offset="1" class="e3mnddh_y"/></linearGradient><linearGradient id="iWmza9d" x1="20.238" x2="20.644" y1="4.695" y2="6.258" gradientUnits="userSpaceOnUse"><stop class="y9kjuab5s"/><stop offset="1" class="ib1ohebew"/></linearGradient><linearGradient id="iuil5Jb" x1="21.206" x2="23.186" y1="10.508" y2="11.415" gradientUnits="userSpaceOnUse"><stop class="gnllp6b4n"/><stop offset="1" class="e3mnddh_y"/></linearGradient><linearGradient id="ikxvmUc" x1="20.363" x2="22.033" y1="9.227" y2="10.011" gradientUnits="userSpaceOnUse"><stop class="fdvg5x26h"/><stop offset="1" class="yxpnfcbab"/></linearGradient><linearGradient id="ih80zyB" x1="22.081" x2="24.693" y1="8.68" y2="8.226" gradientUnits="userSpaceOnUse"><stop class="dfdq-7b_b"/><stop offset="1" class="e3mnddh_y"/></linearGradient><linearGradient id="iydQ1Ic" x1="24.675" x2="24.113" y1="19.445" y2="16.57" gradientUnits="userSpaceOnUse"><stop offset=".053" class="ze9n3hndk"/><stop offset="1" class="e3mnddh_y"/></linearGradient><linearGradient id="i9sl0Hb" x1="24.799" x2="25.081" y1="14.512" y2="17.225" gradientUnits="userSpaceOnUse"><stop class="igisjhuzw"/><stop offset="1" class="ali8rebum"/></linearGradient><linearGradient id="iZKhjye" x1="31.238" x2="28.863" y1="15.976" y2="16.82" gradientUnits="userSpaceOnUse"><stop class="sfyoeacdy"/><stop offset="1" class="dv6qylbxs"/></linearGradient><linearGradient id="isG0isd" x1="22.175" x2="21.324" y1="16.603" y2="18.431" gradientUnits="userSpaceOnUse"><stop class="sfyoeacdy"/><stop offset="1" class="dv6qylbxs"/></linearGradient><filter id="iSZJc0d" width="5.453" height="2.883" x="3.206" y="22.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7169_6168" stdDeviation=".375"/></filter><filter id="ifabrdc" width="1.421" height="1.596" x="8.763" y="18.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7169_6168" stdDeviation=".2"/></filter><filter id="iUyf0rd" width="1.627" height="1.84" x="7.179" y="23.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7169_6168" stdDeviation=".2"/></filter><filter id="ihO7AOc" width="5.59" height="2.699" x="4.21" y="17.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7169_6168" stdDeviation=".375"/></filter><filter id="i4Odjnc" width="1.672" height="2.508" x="16.285" y="21.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7169_6168" stdDeviation=".25"/></filter><filter id="i0RutYV" width="2.458" height="2.476" x="15.685" y="13.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7169_6168" stdDeviation=".375"/></filter><filter id="iYxmeTb" width="2.234" height="1.859" x="10.644" y="20.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7169_6168" stdDeviation=".25"/></filter><filter id="iNoHktb" width="3.394" height="3.726" x="26.942" y="14.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7169_6168" stdDeviation=".5"/></filter><filter id="ifw69Ce" width="3.195" height="3.258" x="24.381" y="3.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7169_6168" stdDeviation=".5"/></filter><filter id="iVbeBMd" width="1.984" height="2.75" x="20.331" y="16.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7169_6168" stdDeviation=".125"/></filter><radialGradient id="i0vaA5d" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 -.28125 .26054 2.0843 1.956 24.164)" gradientUnits="userSpaceOnUse"><stop class="bj6ok_qjs"/><stop offset="1" class="wa36eza7h"/></radialGradient><radialGradient id="irQ6J1m" cx="0" cy="0" r="1" gradientTransform="matrix(2.40625 0 0 2.1136 7.988 14.948)" gradientUnits="userSpaceOnUse"><stop class="yvlj3_bma"/><stop offset="1" class="bfjmklb4x"/></radialGradient><radialGradient id="iomE58X" cx="0" cy="0" r="1" gradientTransform="matrix(1.59375 -2.28125 15.11488 10.55971 9.144 24.195)" gradientUnits="userSpaceOnUse"><stop class="cerjmceuw"/><stop offset="1" class="whgjlv6nh"/></radialGradient><radialGradient id="ig8yNNd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.25 0 0 -41.4107 19.738 22.574)" gradientUnits="userSpaceOnUse"><stop class="xsxuxu8jk"/><stop offset="1" class="ovk0vwb3v"/></radialGradient><radialGradient id="ieQSVue" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 -.125 .18074 6.50649 13.863 9.258)" gradientUnits="userSpaceOnUse"><stop class="lt8ojbcfj"/><stop offset="1" class="lptzej88z"/></radialGradient><radialGradient id="iIY08Dd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1875 1.84375 -1.71646 -2.03648 27.8 5.07)" gradientUnits="userSpaceOnUse"><stop class="sfyoeacdy"/><stop offset="1" class="dv6qylbxs"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:zzz" /></template>
<style>
.ali8rebum {
  stop-color: var(--svg-color--458fca, #458FCA);
  stop-opacity: 0;
}

.bfjmklb4x {
  stop-color: var(--svg-color--3995d2, #3995D2);
  stop-opacity: 0;
}

.bj6ok_qjs {
  stop-color: var(--svg-color--6b93ba, #6B93BA);
}

.bzfh-z_gy {
  d: path("m22.398 8.438l-4.787 9.115a1.7 1.7 0 1 0 3.01 1.581l6.245-11.893l-2.02.542z");
}

.cdvqqhbzt {
  cx: 7.993px;
  cy: 24.913px;
  fill: var(--svg-color--9dd7ff, #9DD7FF);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  rx: 0.398px;
  ry: 0.531px;
}

.cerjmceuw {
  stop-color: var(--svg-color--4b9dff, #4B9DFF);
}

.dfdq-7b_b {
  stop-color: var(--svg-color--1f56f1, #1F56F1);
}

.dv6qylbxs {
  stop-color: var(--svg-color--5cb8ff, #5CB8FF);
  stop-opacity: 0;
}

.e3mnddh_y {
  stop-color: var(--svg-color--4374ff, #4374FF);
  stop-opacity: 0;
}

.ee-0mbo1l {
  d: path("M9.612 20.07a.9.9 0 1 0-1.025-1.479l-5.89 4.079l2.34.57z");
}

.fb97-rokv {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-8px, 1.8px);
  d: path("m2.89 23.631l4.82 1.195");
}

.fdvg5x26h {
  stop-color: var(--svg-color--1e56a9, #1E56A9);
}

.fi_-1x0ja {
  stroke: var(--svg-color--9dd7ff, #9DD7FF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m4.206 23.453l3.454.883");
}

.folzcdcsp {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-8px, 1.8px);
  d: path("M4.293 18.123L9.1 19.33l-6.21 4.3l4.82 1.195");
}

.ft5dv1b6b {
  fill: none;
}

.fx494ib8z {
  d: path("M25.347 4.242L23.59 6.737l-1.203 1.708l-5.423 1.29a1.7 1.7 0 0 1-.787-3.309z");
}

.fxx7_5beg {
  stop-color: var(--svg-color--3a92fb, #3A92FB);
}

.gd8-swbym {
  stroke: var(--svg-color--8aeaff, #8AEAFF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m12.253 21.367l-.984.61");
}

.gnllp6b4n {
  stop-color: var(--svg-color--2e64fd, #2E64FD);
}

.gz-ocqbdf {
  stroke: var(--svg-color--3999ff, #3999FF);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--3-4px, 3.4px);
  d: path("m16.57 8.08l9.068-2.156l-6.522 12.42l9.016-2.131");
}

.h4_a-qv0l {
  cx: 17.12px;
  cy: 22.527px;
  fill: var(--svg-color--8aeaff, #8AEAFF);
  rx: 0.336px;
  ry: 0.754px;
}

.ha1-wccoj {
  d: path("M4.502 17.242a.9.9 0 1 0-.438 1.746l2.91.731l2.213-1.3z");
}

.ib1ohebew {
  stop-color: var(--svg-color--4297c4, #4297C4);
  stop-opacity: 0;
}

.igisjhuzw {
  stop-color: var(--svg-color--3d82b9, #3D82B9);
}

.ipst9caif {
  fill-rule: evenodd;
  d: path("M29.787 15.822a1.7 1.7 0 0 1-1.264 2.045l-9.016 2.13a1.7 1.7 0 0 1-.782-3.308l9.016-2.13a1.7 1.7 0 0 1 2.046 1.263");
}

.jboc_e3pk {
  stroke: var(--svg-color--48d4ff, #48D4FF);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M9.868 14.948h6.626l-6.626 7.626h6.626");
}

.k0t3t2b1f {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M9.868 22.574h6.626");
}

.kdy_2lb4q {
  stop-color: var(--svg-color--8188ff, #8188FF);
}

.labw8tusy {
  stop-color: var(--svg-color--92c7f8, #92C7F8);
  stop-opacity: 0;
}

.lhv0y9mvb {
  stroke: var(--svg-color--9dd7ff, #9DD7FF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m5.085 17.902l3.84.95");
}

.lptzej88z {
  stop-color: var(--svg-color--2f6fc8, #2F6FC8);
  stop-opacity: 0;
}

.lt8ojbcfj {
  stop-color: var(--svg-color--2f6fc8, #2F6FC8);
}

.n95_0b18g {
  stop-color: var(--svg-color--2580ee, #2580EE);
}

.n9zlqmbye {
  cx: 16.914px;
  cy: 14.58px;
  fill: var(--svg-color--8aeaff, #8AEAFF);
  rx: 0.462px;
  ry: 0.504px;
}

.nltn9obzl {
  stroke: var(--svg-color--92c7f8, #92C7F8);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-8px, 1.8px);
  d: path("M4.293 18.123L9.1 19.33l-6.21 4.3l4.82 1.195");
}

.ovk0vwb3v {
  stop-color: var(--svg-color--99eaff, #99EAFF);
  stop-opacity: 0;
}

.p9_e_gy1n {
  d: path("m16 13.698l-2.254 2.5H9.958a1.25 1.25 0 0 1 0-2.5z");
}

.pxepw_zdb {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M9.868 14.948h6.626l-6.626 7.626h6.626");
}

.rrpuvcblk {
  d: path("m19.766 19.937l2.558-4.098l5.417-1.28a1.7 1.7 0 0 1 .782 3.308z");
}

.sfyoeacdy {
  stop-color: var(--svg-color--5cb8ff, #5CB8FF);
}

.t1m-b_8qj {
  cx: 28.639px;
  cy: 16px;
  fill: var(--svg-color--5cb8ff, #5CB8FF);
  rx: 0.681px;
  ry: 0.875px;
}

.touikd5wi {
  cx: 25.978px;
  cy: 5.515px;
  fill: var(--svg-color--5cb8ff, #5CB8FF);
  rx: 0.533px;
  ry: 0.684px;
}

.v3dlubcaj {
  stop-color: var(--svg-color--348ffd, #348FFD);
}

.vfija0yvh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m21.94 16.43l-1.234 2");
}

.vmsdv5b9s {
  d: path("M23.957 6.18L22.39 8.438l2.473-.649l.593-.781z");
}

.w6q68ccus {
  d: path("m8.924 21.754l4.823-5.55l1.085-1.212h1.296c.066.039 1.126-1.04 1.185-.988a1.25 1.25 0 0 1 .124 1.764l-4.824 5.552h-1L10.3 23.747a1.25 1.25 0 0 1-1.376-1.993");
}

.w7yxd49je {
  cx: 9.473px;
  cy: 19.227px;
  fill: var(--svg-color--9dd7ff, #9DD7FF);
  rx: 0.303px;
  ry: 0.403px;
}

.wa36eza7h {
  stop-color: var(--svg-color--6b93ba, #6B93BA);
  stop-opacity: 0;
}

.whgjlv6nh {
  stop-color: var(--svg-color--4b9dff, #4B9DFF);
  stop-opacity: 0;
}

.xsxuxu8jk {
  stop-color: var(--svg-color--85e6ff, #85E6FF);
}

.xx9nt_bnq {
  stop-color: var(--svg-color--2a56d1, #2A56D1);
}

.y9kjuab5s {
  stop-color: var(--svg-color--4297c4, #4297C4);
}

.yvlj3_bma {
  stop-color: var(--svg-color--3995d2, #3995D2);
}

.yxpnfcbab {
  stop-color: var(--svg-color--2f6ac0, #2F6AC0);
  stop-opacity: 0;
}

.ze9n3hndk {
  stop-color: var(--svg-color--2c5fed, #2C5FED);
}

.zik3cd9jy {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--3-4px, 3.4px);
  d: path("m16.57 8.08l9.068-2.156l-6.522 12.42l9.016-2.131");
}

</style>
