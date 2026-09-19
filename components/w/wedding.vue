<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iK7zgOc)"><path class="nt52r6gsz"/></g><path fill="url(#irFsJeb)" class="l9898gsvk"/><path fill="url(#ilJEEKM)" class="l9898gsvk"/><path fill="url(#ik4JXVd)" class="l9898gsvk"/><path fill="url(#iuKD3nd)" class="l9898gsvk"/><path fill="url(#iFtVtKc)" class="l9898gsvk"/><g filter="url(#iEr8fBW)"><path fill="url(#io27mkb)" class="oxe86ubxt"/></g><path class="a8qcv-bem"/><path fill="url(#iQIEFSD)" class="qybs2bgwi"/><path fill="url(#iYCjEgd)" class="qybs2bgwi"/><path fill="url(#iW7KLib)" class="qybs2bgwi"/><path fill="url(#iKOkKTa)" class="qybs2bgwi"/><g filter="url(#ia2XZFe)"><path fill="url(#ifBxDNb)" class="zttr32brq"/></g><g filter="url(#i99ctXd)"><path fill="url(#i0sN7qe)" class="zr4klxbhd"/></g><g filter="url(#ihLo7Qc)"><path fill="url(#ils2GLb)" class="z4rj90-6k"/></g><g filter="url(#i5wna3p)"><path fill="url(#ils2GLb)" class="z4rj90-6k"/></g><path fill="url(#iL2Wtcc)" class="e06--pyti"/><path fill="url(#ixCbC7d)" class="u0_k3rb8b"/><path fill="url(#iQWkxfc)" class="u0_k3rb8b"/><path fill="url(#i5wia1Q)" class="u0_k3rb8b"/><g filter="url(#ipwMofc)"><path fill="url(#i8Bf9me)" class="z4lbobb-j"/><path fill="url(#ic4jxNy)" class="z4lbobb-j"/><path fill="url(#ijaOp3b)" class="z4lbobb-j"/><path fill="url(#ilp6q0d)" class="z4lbobb-j"/></g><g filter="url(#idCAyLb)"><path class="f60wg4b-j"/></g><g filter="url(#ic3H9Cc)"><path class="wfd8n6c-u"/></g><g filter="url(#i5hDilw)"><path fill="url(#iCaqdwe)" class="morutttoc"/></g><defs><linearGradient id="irFsJeb" x1="16.62" x2="30.62" y1="23.002" y2="23.002" gradientUnits="userSpaceOnUse"><stop class="txjl1cc2k"/><stop offset="1" class="zuru489zf"/></linearGradient><linearGradient id="ilJEEKM" x1="22" x2="22" y1="18.871" y2="19.191" gradientUnits="userSpaceOnUse"><stop class="f4d4f3b0t"/><stop offset="1" class="sj9-kib2k"/></linearGradient><linearGradient id="ik4JXVd" x1="28.856" x2="27.355" y1="24.09" y2="24.09" gradientUnits="userSpaceOnUse"><stop class="b7qc61bdg"/><stop offset="1" class="b3tvl8bnj"/></linearGradient><linearGradient id="iuKD3nd" x1="29" x2="28.586" y1="23.775" y2="23.775" gradientUnits="userSpaceOnUse"><stop offset=".415" class="jdvpstbdm"/><stop offset="1" class="d4tyr2b7y"/></linearGradient><linearGradient id="iFtVtKc" x1="15" x2="15.951" y1="24.722" y2="24.722" gradientUnits="userSpaceOnUse"><stop class="dcevrspgc"/><stop offset="1" class="rvzlycbow"/></linearGradient><linearGradient id="io27mkb" x1="21.5" x2="21.5" y1="16.19" y2="19" gradientUnits="userSpaceOnUse"><stop class="jg3zrdbka"/><stop offset="1" class="m619ir2ck"/></linearGradient><linearGradient id="iQIEFSD" x1="15" x2="13.608" y1="21.099" y2="21.099" gradientUnits="userSpaceOnUse"><stop class="q01f0zb6c"/><stop offset="1" class="ovh_dwxvc"/></linearGradient><linearGradient id="iYCjEgd" x1="12.655" x2="12.164" y1="10.763" y2="11.462" gradientUnits="userSpaceOnUse"><stop class="w82u0v2cx"/><stop offset="1" class="n8spe85hy"/></linearGradient><linearGradient id="iW7KLib" x1="4" x2="5.11" y1="21.324" y2="21.324" gradientUnits="userSpaceOnUse"><stop class="svuw-xb9i"/><stop offset="1" class="lx62tvwyt"/></linearGradient><linearGradient id="ifBxDNb" x1="6" x2="13" y1="26.419" y2="26.476" gradientUnits="userSpaceOnUse"><stop class="y6comkb_y"/><stop offset="1" class="fvbfgdp5c"/></linearGradient><linearGradient id="i0sN7qe" x1="18.168" x2="22.332" y1="27" y2="22.549" gradientUnits="userSpaceOnUse"><stop class="xq6-q6bzl"/><stop offset="1" class="kxfyafbtp"/></linearGradient><linearGradient id="ils2GLb" x1="23.168" x2="27.332" y1="27" y2="22.549" gradientUnits="userSpaceOnUse"><stop class="xq6-q6bzl"/><stop offset="1" class="kxfyafbtp"/></linearGradient><linearGradient id="iL2Wtcc" x1="7.09" x2="11.913" y1="16.153" y2="14.861" gradientUnits="userSpaceOnUse"><stop class="zmtvao2qz"/><stop offset=".212" class="njmh6acfb"/><stop offset=".519" class="cbepfyc1p"/><stop offset=".792" class="z3g7vxovl"/><stop offset="1" class="cp65m-qgt"/></linearGradient><linearGradient id="ixCbC7d" x1="9.505" x2="9.505" y1="30" y2="28.454" gradientUnits="userSpaceOnUse"><stop class="or6lixbfy"/><stop offset="1" class="m9va0zemj"/></linearGradient><linearGradient id="iQWkxfc" x1="5" x2="5.839" y1="29.89" y2="29.89" gradientUnits="userSpaceOnUse"><stop class="p0w_ybcst"/><stop offset="1" class="nuhe8ac9o"/></linearGradient><linearGradient id="i5wia1Q" x1="14" x2="13.251" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="z3_rxfb8q"/><stop offset="1" class="ftxms8s4w"/></linearGradient><linearGradient id="i8Bf9me" x1="22.51" x2="22.51" y1="8" y2="13.664" gradientUnits="userSpaceOnUse"><stop class="u56xkml5d"/><stop offset="1" class="ku_3hrg3y"/></linearGradient><linearGradient id="iCaqdwe" x1="2" x2="17" y1="10.502" y2="10.502" gradientUnits="userSpaceOnUse"><stop class="y0o95ws0b"/><stop offset="1" class="fs0brobun"/></linearGradient><filter id="iK7zgOc" width="3.25" height="6.3" x="8" y="3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.227451 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6910"/></filter><filter id="iEr8fBW" width="17.25" height="3.2" x="12.75" y="15.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.356863 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6910"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.211765 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6910" result="effect2_innerShadow_18_6910"/></filter><filter id="ia2XZFe" width="7.9" height="7.25" x="5.5" y="22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.180392 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6910"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.117647 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6910" result="effect2_innerShadow_18_6910"/></filter><filter id="i99ctXd" width="3.5" height="6.25" x="17.76" y="21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.964706 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6910"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.165625 0 0 0 0 0.589906 0 0 0 0 0.883333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6910" result="effect2_innerShadow_18_6910"/></filter><filter id="ihLo7Qc" width="3.5" height="6.25" x="22.76" y="21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.964706 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6910"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.209063 0 0 0 0 0.63476 0 0 0 0 0.929167 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6910" result="effect2_innerShadow_18_6910"/></filter><filter id="i5wna3p" width="3.5" height="6.25" x="22.76" y="21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.964706 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6910"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.165625 0 0 0 0 0.589906 0 0 0 0 0.883333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6910" result="effect2_innerShadow_18_6910"/></filter><filter id="ipwMofc" width="7.75" height="6.1" x="19.01" y="7.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".8" dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.137255 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6910"/></filter><filter id="idCAyLb" width="3.162" height="1.1" x="8" y="3.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6910" stdDeviation=".2"/></filter><filter id="ic3H9Cc" width="1.1" height="5.116" x="9.031" y="2.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6910" stdDeviation=".2"/></filter><filter id="i5hDilw" width="15.4" height="6.7" x="1.85" y="6.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.152941 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6910"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.298039 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6910" result="effect2_innerShadow_18_6910"/></filter><radialGradient id="iKOkKTa" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25487 0 0 -2.04182 15.479 12.552)" gradientUnits="userSpaceOnUse"><stop class="ieb91pgra"/><stop offset="1" class="kys058bmo"/></radialGradient><radialGradient id="ic4jxNy" cx="0" cy="0" r="1" gradientTransform="matrix(.76563 -1.3875 .82176 .45345 23.021 8.337)" gradientUnits="userSpaceOnUse"><stop class="ogcvnibsz"/><stop offset="1" class="d032wwa1g"/></radialGradient><radialGradient id="ijaOp3b" cx="0" cy="0" r="1" gradientTransform="rotate(138.156 11.29 9.46)scale(2.64201 3.57526)" gradientUnits="userSpaceOnUse"><stop class="d_fo324un"/><stop offset="1" class="go_bdo91j"/></radialGradient><radialGradient id="ilp6q0d" cx="0" cy="0" r="1" gradientTransform="rotate(141.985 9.082 8.38)scale(1.1569 1.57134)" gradientUnits="userSpaceOnUse"><stop class="d_fo324un"/><stop offset="1" class="go_bdo91j"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wedding" /></template>
<style>
.a8qcv-bem {
  fill: var(--svg-color--ffb09b, #FFB09B);
  d: path("M15 30H4V11.5L9.51 8L15 11.5z");
}

.b3tvl8bnj {
  stop-color: var(--svg-color--ffd3af, #FFD3AF);
  stop-opacity: 0;
}

.b7qc61bdg {
  stop-color: var(--svg-color--ffd3af, #FFD3AF);
}

.cbepfyc1p {
  stop-color: var(--svg-color--37daf4, #37DAF4);
}

.cp65m-qgt {
  stop-color: var(--svg-color--4cf0f8, #4CF0F8);
}

.d_fo324un {
  stop-color: var(--svg-color--ff4d84, #FF4D84);
}

.d032wwa1g {
  stop-color: var(--svg-color--bc2e4f, #BC2E4F);
  stop-opacity: 0;
}

.d4tyr2b7y {
  stop-color: var(--svg-color--fdcdad, #FDCDAD);
  stop-opacity: 0;
}

.dcevrspgc {
  stop-color: var(--svg-color--e37e6a, #E37E6A);
}

.e06--pyti {
  d: path("M9.5 18A2.5 2.5 0 0 1 7 15.5C7 14.121 8.121 13 9.5 13s2.5 1.121 2.5 2.5c0 1.389-1.121 2.5-2.5 2.5");
}

.f4d4f3b0t {
  stop-color: var(--svg-color--b55a62, #B55A62);
}

.f60wg4b-j {
  stroke: var(--svg-color--a0776e, #A0776E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M8.55 4.45h2.062");
}

.fs0brobun {
  stop-color: var(--svg-color--eb335c, #EB335C);
}

.ft5dv1b6b {
  fill: none;
}

.ftxms8s4w {
  stop-color: var(--svg-color--b6aebc, #B6AEBC);
  stop-opacity: 0;
}

.fvbfgdp5c {
  stop-color: var(--svg-color--46204c, #46204C);
}

.go_bdo91j {
  stop-color: var(--svg-color--ff4d84, #FF4D84);
  stop-opacity: 0;
}

.ieb91pgra {
  stop-color: var(--svg-color--c03e47, #C03E47);
}

.jdvpstbdm {
  stop-color: var(--svg-color--fdcdad, #FDCDAD);
}

.jg3zrdbka {
  stop-color: var(--svg-color--ea376f, #EA376F);
}

.ku_3hrg3y {
  stop-color: var(--svg-color--e41d4a, #E41D4A);
}

.kxfyafbtp {
  stop-color: var(--svg-color--4db9fc, #4DB9FC);
}

.kys058bmo {
  stop-color: var(--svg-color--c03e47, #C03E47);
  stop-opacity: 0;
}

.l9898gsvk {
  d: path("M29 30H15V16h13.03c.54 0 .97.43.97.97z");
}

.lx62tvwyt {
  stop-color: var(--svg-color--b47a6d, #B47A6D);
  stop-opacity: 0;
}

.m619ir2ck {
  stop-color: var(--svg-color--e0296a, #E0296A);
}

.m9va0zemj {
  stop-color: var(--svg-color--7e7987, #7E7987);
}

.morutttoc {
  d: path("m3.388 13.133l5.513-3.936c.36-.26.849-.26 1.208 0l5.513 3.936a.871.871 0 1 0 1.009-1.418L10.449 7.3c-.57-.4-1.328-.4-1.898 0L2.37 11.714c-.23.16-.37.43-.37.71c.01.709.819 1.128 1.388.709");
}

.n8spe85hy {
  stop-color: var(--svg-color--c1424f, #C1424F);
  stop-opacity: 0;
}

.njmh6acfb {
  stop-color: var(--svg-color--1ebfee, #1EBFEE);
}

.nt52r6gsz {
  fill: var(--svg-color--8f6058, #8F6058);
  d: path("M10.5 4h-.4a.1.1 0 0 1-.1-.1v-.4c0-.28-.22-.5-.5-.5s-.5.22-.5.5v.4a.1.1 0 0 1-.1.1h-.4c-.28 0-.5.22-.5.5s.22.5.5.5h.4a.1.1 0 0 1 .1.1v3.7c0 .28.22.5.5.5s.5-.22.5-.5V5.1a.1.1 0 0 1 .1-.1h.4c.28 0 .5-.22.5-.5c0-.27-.22-.5-.5-.5");
}

.nuhe8ac9o {
  stop-color: var(--svg-color--796f81, #796F81);
  stop-opacity: 0;
}

.ogcvnibsz {
  stop-color: var(--svg-color--bc2e4f, #BC2E4F);
}

.or6lixbfy {
  stop-color: var(--svg-color--9d92aa, #9D92AA);
}

.ovh_dwxvc {
  stop-color: var(--svg-color--ffcba9, #FFCBA9);
  stop-opacity: 0;
}

.oxe86ubxt {
  d: path("m13.051 18.093l.548-1.346a1.19 1.19 0 0 1 1.116-.737L28.296 16c.487 0 .933.289 1.116.738l.538 1.315a.692.692 0 0 1-.65.947H13.69c-.497 0-.821-.468-.639-.907");
}

.p0w_ybcst {
  stop-color: var(--svg-color--796f81, #796F81);
}

.q01f0zb6c {
  stop-color: var(--svg-color--ffcba9, #FFCBA9);
}

.qybs2bgwi {
  d: path("M15 30H4V11.5L9.51 8L15 11.5z");
}

.rvzlycbow {
  stop-color: var(--svg-color--e37e6a, #E37E6A);
  stop-opacity: 0;
}

.sj9-kib2k {
  stop-color: var(--svg-color--b55a62, #B55A62);
  stop-opacity: 0;
}

.svuw-xb9i {
  stop-color: var(--svg-color--b47a6d, #B47A6D);
}

.txjl1cc2k {
  stop-color: var(--svg-color--ffb19b, #FFB19B);
}

.u0_k3rb8b {
  d: path("M14 30H5c0-.55.45-1 1-1h7c.56 0 1 .45 1 1");
}

.u56xkml5d {
  stop-color: var(--svg-color--e93178, #E93178);
}

.w82u0v2cx {
  stop-color: var(--svg-color--c1424f, #C1424F);
}

.wfd8n6c-u {
  stroke: var(--svg-color--a0776e, #A0776E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.581 3.328v4.016");
}

.xq6-q6bzl {
  stop-color: var(--svg-color--51dcff, #51DCFF);
}

.y0o95ws0b {
  stop-color: var(--svg-color--f23449, #F23449);
}

.y6comkb_y {
  stop-color: var(--svg-color--492454, #492454);
}

.z3_rxfb8q {
  stop-color: var(--svg-color--b6aebc, #B6AEBC);
}

.z3g7vxovl {
  stop-color: var(--svg-color--47eaf7, #47EAF7);
}

.z4lbobb-j {
  d: path("M26.01 9.79v.04c0 .56-.17 1.09-.46 1.52c-.72 1-1.63 1.87-2.67 2.55c-.11.07-.24.1-.37.1s-.26-.03-.37-.1c-1.04-.68-1.95-1.55-2.67-2.55c-.29-.43-.46-.96-.46-1.52v-.04c.01-1 .81-1.79 1.8-1.79c.14 0 .29.02.42.06c.5.1.92.42 1.16.85c.03.05.07.07.12.07s.09-.02.12-.07c.24-.43.66-.75 1.16-.85c.13-.04.28-.06.42-.06c.99 0 1.79.79 1.8 1.79");
}

.z4rj90-6k {
  d: path("M26.01 27h-3v-4.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5z");
}

.zmtvao2qz {
  stop-color: var(--svg-color--08a8ea, #08A8EA);
}

.zr4klxbhd {
  d: path("M21.01 27h-3v-4.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5z");
}

.zttr32brq {
  d: path("M13 29H6v-3.5C6 23.57 7.57 22 9.5 22s3.5 1.57 3.5 3.5z");
}

.zuru489zf {
  stop-color: var(--svg-color--ffad9a, #FFAD9A);
}

</style>
