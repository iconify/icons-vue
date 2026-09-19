<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iWQyfZc)"><rect class="vpi88sy-b"/></g><rect fill="url(#i7ZSb3J)" class="lqrj1uqgb"/><path fill="url(#i2DTmKc)" class="ke-o5ughy"/><path fill="url(#i0hz3nn)" class="s-2sxacyb"/><path fill="url(#idogsJe)" class="s-2sxacyb"/><path fill="url(#ikQSLce)" class="er_ehcala"/><path fill="url(#ih8A8Bb)" class="er_ehcala"/><g filter="url(#iGdE6hd)"><path fill="url(#iawLVtd)" class="dmzl4zbhd"/></g><path fill="url(#iPayKFc)" class="dmzl4zbhd"/><path fill="url(#iiqQLGe)" class="dmzl4zbhd"/><path fill="url(#ipxcBNm)" class="khmdigrpr"/><path fill="url(#ihgCkeQ)" class="khmdigrpr"/><g filter="url(#iPGbTRb)"><path fill="url(#iVS8Bfc)" class="k2-31jbsp"/><path fill="url(#i2ppgAb)" class="k2-31jbsp"/></g><path fill="url(#ii3LSgb)" class="k2-31jbsp"/><path fill="url(#i1Rlgwc)" class="m7987sb8f"/><path fill="url(#iQ5yB2b)" class="m7987sb8f"/><path fill="url(#iyTxrVd)" class="m7987sb8f"/><path fill="url(#iAk8zwd)" class="m7987sb8f"/><path fill="url(#iE4Zf4b)" class="hn5gnib9j"/><path fill="url(#ia8Ljcd)" class="h_ubhab8d"/><path fill="url(#iN6GHRb)" class="uur93nf6f"/><path fill="url(#iKl4vdd)" class="uur93nf6f"/><g filter="url(#iixQsVg)"><rect class="vcjn16b4a"/><rect fill="url(#iQXlRte)" class="eik98hb1x"/><rect fill="url(#iQRQqPe)" class="eik98hb1x"/></g><defs><linearGradient id="i7ZSb3J" x1="12.892" x2="13.384" y1="10.824" y2="10.824" gradientUnits="userSpaceOnUse"><stop class="o5dmsej8j"/><stop offset="1" class="bok-e4btv"/></linearGradient><linearGradient id="i2DTmKc" x1="5.996" x2="25.996" y1="15.471" y2="15.471" gradientUnits="userSpaceOnUse"><stop class="i2us4nwod"/><stop offset=".997" class="mc-5al3bu"/></linearGradient><linearGradient id="i0hz3nn" x1="4.996" x2="8.579" y1="27.971" y2="27.971" gradientUnits="userSpaceOnUse"><stop class="d0dtf55ki"/><stop offset="1" class="xqwtf131s"/></linearGradient><linearGradient id="idogsJe" x1="7" x2="7" y1="25.81" y2="26.813" gradientUnits="userSpaceOnUse"><stop class="jdx_54brl"/><stop offset="1" class="dwwmgshuz"/></linearGradient><linearGradient id="ikQSLce" x1="22.996" x2="26.579" y1="27.615" y2="27.615" gradientUnits="userSpaceOnUse"><stop class="d0dtf55ki"/><stop offset="1" class="xqwtf131s"/></linearGradient><linearGradient id="ih8A8Bb" x1="25" x2="25" y1="25.069" y2="26.25" gradientUnits="userSpaceOnUse"><stop class="jdx_54brl"/><stop offset="1" class="dwwmgshuz"/></linearGradient><linearGradient id="iawLVtd" x1="15.996" x2="15.996" y1="25.119" y2="17.158" gradientUnits="userSpaceOnUse"><stop class="ml_m0hbhs"/><stop offset="1" class="t8i2je_sv"/></linearGradient><linearGradient id="iPayKFc" x1="16.005" x2="16.005" y1="25.969" y2="24.125" gradientUnits="userSpaceOnUse"><stop class="p6fvmhb5l"/><stop offset="1" class="yssxmac5f"/></linearGradient><linearGradient id="iiqQLGe" x1="16.005" x2="16.005" y1="25.969" y2="25.719" gradientUnits="userSpaceOnUse"><stop class="u598t1tla"/><stop offset="1" class="ysjyd1b3i"/></linearGradient><linearGradient id="ipxcBNm" x1="28" x2="25.704" y1="20.969" y2="24.594" gradientUnits="userSpaceOnUse"><stop class="cbzz_pbzk"/><stop offset="1" class="t4mttwb0j"/></linearGradient><linearGradient id="ihgCkeQ" x1="28" x2="27.517" y1="20.719" y2="22.125" gradientUnits="userSpaceOnUse"><stop class="uu_6m-ozf"/><stop offset="1" class="ct8zwjbcw"/></linearGradient><linearGradient id="iVS8Bfc" x1="4.704" x2="4.704" y1="20.969" y2="23.969" gradientUnits="userSpaceOnUse"><stop class="cbzz_pbzk"/><stop offset="1" class="t4mttwb0j"/></linearGradient><linearGradient id="i2ppgAb" x1="5.736" x2="5.736" y1="20.625" y2="21.531" gradientUnits="userSpaceOnUse"><stop class="uu_6m-ozf"/><stop offset="1" class="ct8zwjbcw"/></linearGradient><linearGradient id="ii3LSgb" x1="5.986" x2="5.986" y1="24.156" y2="23.063" gradientUnits="userSpaceOnUse"><stop class="g-0eyi33h"/><stop offset="1" class="o2qh0zbqu"/></linearGradient><linearGradient id="i1Rlgwc" x1="6.996" x2="24.996" y1="14.971" y2="14.971" gradientUnits="userSpaceOnUse"><stop class="atvo3bbca"/><stop offset="1" class="hnr_bab9e"/></linearGradient><linearGradient id="iQ5yB2b" x1="7.572" x2="9.84" y1="15.646" y2="16.137" gradientUnits="userSpaceOnUse"><stop class="nui9eubax"/><stop offset="1" class="ok746vaaq"/></linearGradient><linearGradient id="iyTxrVd" x1="24.434" x2="21.599" y1="15.835" y2="16.477" gradientUnits="userSpaceOnUse"><stop class="zj6-whbyb"/><stop offset="1" class="lo7ye45ke"/></linearGradient><linearGradient id="iAk8zwd" x1="24.829" x2="24.11" y1="15.484" y2="15.656" gradientUnits="userSpaceOnUse"><stop class="p967w33yz"/><stop offset="1" class="c2di20hqg"/></linearGradient><linearGradient id="iN6GHRb" x1="15.99" x2="15.99" y1="17.317" y2="19.969" gradientUnits="userSpaceOnUse"><stop class="qbfcipoys"/><stop offset="1" class="cn-d5abbz"/></linearGradient><linearGradient id="iKl4vdd" x1="15.99" x2="15.99" y1="16.969" y2="17.5" gradientUnits="userSpaceOnUse"><stop class="j02ji9vgs"/><stop offset="1" class="t_ul19bax"/></linearGradient><radialGradient id="iE4Zf4b" cx="0" cy="0" r="1" gradientTransform="rotate(-154.291 8.147 10.401)scale(3.26228 3.22874)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="ghh7gsb2r"/><stop offset="1" class="cwkwtwl9t"/></radialGradient><radialGradient id="ia8Ljcd" cx="0" cy="0" r="1" gradientTransform="rotate(-154.291 14.631 8.921)scale(3.26228 3.22874)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="ghh7gsb2r"/><stop offset="1" class="cwkwtwl9t"/></radialGradient><radialGradient id="iQXlRte" cx="0" cy="0" r="1" gradientTransform="matrix(1.84375 0 0 2.62961 11.83 23.188)" gradientUnits="userSpaceOnUse"><stop class="sb8wjubjk"/><stop offset="1" class="vgix48bbk"/></radialGradient><radialGradient id="iQRQqPe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9375 0 0 -2.83803 20.33 22.46)" gradientUnits="userSpaceOnUse"><stop class="dpcsiy5ry"/><stop offset="1" class="hcvwyibga"/></radialGradient><filter id="iWQyfZc" width="7.004" height="3.648" x="12.503" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.439216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10484"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.968627 0 0 0 0 0.945098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10484" result="effect2_innerShadow_18_10484"/></filter><filter id="iGdE6hd" width="25.26" height="9.01" x="3.75" y="16.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.576471 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10484"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.823529 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10484" result="effect2_innerShadow_18_10484"/></filter><filter id="iPGbTRb" width="3.3" height="3" x="3.7" y="20.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.737255 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10484"/></filter><filter id="iixQsVg" width="7.938" height="3.703" x="12.021" y="20.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.305882 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10484"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oncoming-taxi" /></template>
<style>
.atvo3bbca {
  stop-color: var(--svg-color--46c4f7, #46C4F7);
}

.bok-e4btv {
  stop-color: var(--svg-color--827f7f, #827F7F);
  stop-opacity: 0;
}

.c2di20hqg {
  stop-color: var(--svg-color--56d4f6, #56D4F6);
  stop-opacity: 0;
}

.cbzz_pbzk {
  stop-color: var(--svg-color--dac3ea, #DAC3EA);
}

.cn-d5abbz {
  stop-color: var(--svg-color--ff9e43, #FF9E43);
}

.ct8zwjbcw {
  stop-color: var(--svg-color--c1a4d6, #C1A4D6);
  stop-opacity: 0;
}

.cwkwtwl9t {
  stop-color: var(--svg-color--ff6f39, #FF6F39);
}

.d0dtf55ki {
  stop-color: var(--svg-color--1f204c, #1F204C);
}

.dmzl4zbhd {
  d: path("M26.64 25.969H5.36c-.75 0-1.36-.61-1.36-1.36v-4.72c0-1.62 1.31-2.93 2.93-2.93h18.15c1.62 0 2.93 1.31 2.93 2.93v4.72c-.01.75-.62 1.36-1.37 1.36");
}

.dpcsiy5ry {
  stop-color: var(--svg-color--5d5563, #5D5563);
}

.dwwmgshuz {
  stop-color: var(--svg-color--2b143c, #2B143C);
  stop-opacity: 0;
}

.eik98hb1x {
  width: 7.938px;
  height: 2.953px;
  x: 12.021px;
  y: 20.984px;
  rx: 1.3px;
}

.er_ehcala {
  d: path("M25.88 29.969h-1.76c-.62 0-1.12-.5-1.12-1.12V22.53h4v6.318c0 .62-.51 1.12-1.12 1.12");
}

.ft5dv1b6b {
  fill: none;
}

.g-0eyi33h {
  stop-color: var(--svg-color--f2eaf8, #F2EAF8);
}

.ghh7gsb2r {
  stop-color: var(--svg-color--fd9f3e, #FD9F3E);
}

.h_ubhab8d {
  d: path("M22.474 23.879c.812 0 1.47-.647 1.47-1.445c0-.799-.658-1.446-1.47-1.446s-1.47.647-1.47 1.446s.659 1.445 1.47 1.445");
}

.hcvwyibga {
  stop-color: var(--svg-color--5d5563, #5D5563);
  stop-opacity: 0;
}

.hn5gnib9j {
  d: path("M9.506 23.879c.811 0 1.47-.647 1.47-1.445c0-.799-.659-1.446-1.47-1.446c-.812 0-1.47.647-1.47 1.446s.658 1.445 1.47 1.445");
}

.hnr_bab9e {
  stop-color: var(--svg-color--54d3f5, #54D3F5);
}

.i2us4nwod {
  stop-color: var(--svg-color--f7d522, #F7D522);
}

.j02ji9vgs {
  stop-color: var(--svg-color--d0b07e, #D0B07E);
}

.jdx_54brl {
  stop-color: var(--svg-color--2b143c, #2B143C);
}

.k2-31jbsp {
  d: path("M7 21.969c0-.55-.45-1-1-1H4v3h2c.55 0 1-.45 1-1z");
}

.ke-o5ughy {
  d: path("m6 19.969l2.03-6.1c.58-1.73 2.2-2.9 4.02-2.9h7.89c1.82 0 3.44 1.17 4.02 2.9l2.03 6.1z");
}

.khmdigrpr {
  d: path("M25 22.969c0 .55.45 1 1 1h2v-3h-2c-.55 0-1 .45-1 1z");
}

.lo7ye45ke {
  stop-color: var(--svg-color--76efff, #76EFFF);
  stop-opacity: 0;
}

.lqrj1uqgb {
  width: 6.004px;
  height: 3.648px;
  x: 13.003px;
  y: 9px;
  rx: 1.25px;
}

.m7987sb8f {
  d: path("M8.03 13.869L7 16.969h18l-1.03-3.1c-.11-.32-.26-.62-.44-.9H8.47c-.18.28-.33.58-.44.9");
}

.mc-5al3bu {
  stop-color: var(--svg-color--fff175, #FFF175);
}

.ml_m0hbhs {
  stop-color: var(--svg-color--feb243, #FEB243);
}

.nui9eubax {
  stop-color: var(--svg-color--5492b2, #5492B2);
}

.o2qh0zbqu {
  stop-color: var(--svg-color--f2eaf8, #F2EAF8);
  stop-opacity: 0;
}

.o5dmsej8j {
  stop-color: var(--svg-color--827f7f, #827F7F);
}

.ok746vaaq {
  stop-color: var(--svg-color--5492b2, #5492B2);
  stop-opacity: 0;
}

.p6fvmhb5l {
  stop-color: var(--svg-color--d17141, #D17141);
}

.p967w33yz {
  stop-color: var(--svg-color--56d4f6, #56D4F6);
}

.qbfcipoys {
  stop-color: var(--svg-color--ffaf3c, #FFAF3C);
}

.s-2sxacyb {
  d: path("M7.88 29.969H6.12c-.62 0-1.12-.5-1.12-1.12v-5.193h4v5.193c0 .62-.51 1.12-1.12 1.12");
}

.sb8wjubjk {
  stop-color: var(--svg-color--928e95, #928E95);
}

.t_ul19bax {
  stop-color: var(--svg-color--d0b07e, #D0B07E);
  stop-opacity: 0;
}

.t4mttwb0j {
  stop-color: var(--svg-color--fbf0ff, #FBF0FF);
}

.t8i2je_sv {
  stop-color: var(--svg-color--f5c63a, #F5C63A);
}

.u598t1tla {
  stop-color: var(--svg-color--c47882, #C47882);
}

.uu_6m-ozf {
  stop-color: var(--svg-color--c1a4d6, #C1A4D6);
}

.uur93nf6f {
  d: path("M21.56 19.969H10.43c-.79 0-1.44-.64-1.44-1.44v-1.56h14v1.56c.01.8-.64 1.44-1.43 1.44");
}

.vcjn16b4a {
  width: 7.938px;
  height: 2.953px;
  x: 12.021px;
  y: 20.984px;
  fill: var(--svg-color--7a757e, #7A757E);
  rx: 1.3px;
}

.vgix48bbk {
  stop-color: var(--svg-color--928e95, #928E95);
  stop-opacity: 0;
}

.vpi88sy-b {
  width: 6.004px;
  height: 3.648px;
  x: 13.003px;
  y: 9px;
  fill: var(--svg-color--cec4c4, #CEC4C4);
  rx: 1.25px;
}

.xqwtf131s {
  stop-color: var(--svg-color--451f4f, #451F4F);
}

.ysjyd1b3i {
  stop-color: var(--svg-color--c47882, #C47882);
  stop-opacity: 0;
}

.yssxmac5f {
  stop-color: var(--svg-color--d17141, #D17141);
  stop-opacity: 0;
}

.zj6-whbyb {
  stop-color: var(--svg-color--76efff, #76EFFF);
}

</style>
