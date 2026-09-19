<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="ihLmjXb" class="e82rysb7i"/></defs><g class="ft5dv1b6b"><path fill="url(#ivrj1xd)" class="zo_jqkdbv"/><path fill="url(#id0oXKP)" class="zo_jqkdbv"/><path fill="url(#id1cfsb)" class="zo_jqkdbv"/><path fill="url(#i85Leie)" class="zo_jqkdbv"/><path fill="url(#izwUbHe)" class="zo_jqkdbv"/><path fill="url(#i86ll3b)" class="zo_jqkdbv"/><path fill="url(#iGL21cd)" class="zo_jqkdbv"/><path fill="url(#iFzUCnd)" class="zo_jqkdbv"/><path fill="url(#iaGbNtj)" class="zo_jqkdbv"/><path fill="url(#i5s895c)" class="zo_jqkdbv"/><g filter="url(#i71xvwe)"><path fill="url(#i1zDHDc)" class="tdsz55bit"/><path fill="url(#imoCehd)" class="tdsz55bit"/><path fill="url(#iwU8h4d)" class="tdsz55bit"/></g><path fill="url(#i8kOCDb)" class="ysji-m2pv"/><path fill="url(#iDhPpve)" class="ysji-m2pv"/><g filter="url(#iehzpeL)"><use href="#ihLmjXb"/></g><g filter="url(#iz03Vfe)"><use href="#ihLmjXb"/><path fill="url(#iouQj6d)" class="yblikdbdb"/><path fill="url(#i5zZIsW)" class="yblikdbdb"/><path fill="url(#iowq3gc)" class="yblikdbdb"/><path fill="url(#iiEt9yc)" class="yblikdbdb"/></g><defs><radialGradient id="id0oXKP" cx="0" cy="0" r="1" gradientTransform="matrix(-2.05161 1.83726 -1.62103 -1.81016 14.02 4.968)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="q3m8m7bhy"/><stop offset="1" class="vxrp39aul"/></radialGradient><radialGradient id="id1cfsb" cx="0" cy="0" r="1" gradientTransform="matrix(1.65354 4.054 -3.57688 1.45893 6.854 4.098)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="uhy_-rb7u"/><stop offset="1" class="gsrhrkoli"/></radialGradient><radialGradient id="i85Leie" cx="0" cy="0" r="1" gradientTransform="rotate(-164.745 9.854 2.845)scale(1.74567 2.4171)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="izwUbHe" cx="0" cy="0" r="1" gradientTransform="rotate(154.195 9.838 7.897)scale(3.09515 2.28599)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="i86ll3b" cx="0" cy="0" r="1" gradientTransform="rotate(-173.379 11.865 7.32)scale(3.45258 1.94565)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="iGL21cd" cx="0" cy="0" r="1" gradientTransform="rotate(-43.964 34.596 -14.434)scale(3.13177 3.01709)" gradientUnits="userSpaceOnUse"><stop class="kypg0578v"/><stop offset="1" class="yiqe49k2f"/></radialGradient><radialGradient id="iFzUCnd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.747 7.318 8.343)scale(2.40097 2.31305)" gradientUnits="userSpaceOnUse"><stop class="kypg0578v"/><stop offset="1" class="yiqe49k2f"/></radialGradient><radialGradient id="iaGbNtj" cx="0" cy="0" r="1" gradientTransform="matrix(2.2047 1.04112 -1.25835 2.6647 1.924 11.122)" gradientUnits="userSpaceOnUse"><stop class="mulvig9sp"/><stop offset="1" class="a_xm9geyk"/></radialGradient><radialGradient id="i5s895c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25483 -1.731 1.63306 -2.12724 16.478 23.45)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="rwhrj1bde"/><stop offset="1" class="tzt2apygr"/></radialGradient><radialGradient id="i1zDHDc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.5031 12.36612 -15.27094 -8.03069 16.579 9.727)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="mlwsi7b0o"/><stop offset="1" class="hemkrl1wk"/><stop offset="1" class="j756vz6_d"/></radialGradient><radialGradient id="imoCehd" cx="0" cy="0" r="1" gradientTransform="rotate(-140.631 8.034 7.713)scale(4.87402 4.11509)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="aksdkybif"/><stop offset="1" class="chsd9qafy"/></radialGradient><radialGradient id="iwU8h4d" cx="0" cy="0" r="1" gradientTransform="matrix(-16.3279 3.38164 -2.85508 -13.78545 18.531 12.926)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="chsd9qafy"/><stop offset="1" class="aksdkybif"/></radialGradient><radialGradient id="i8kOCDb" cx="0" cy="0" r="1" gradientTransform="rotate(-110.468 12.222 4.816)scale(3.57559 3.47283)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="r02t0tqck"/><stop offset="1" class="nh9jgyb1q"/></radialGradient><radialGradient id="iDhPpve" cx="0" cy="0" r="1" gradientTransform="rotate(-148.811 9.13 6.642)scale(1.44966 4.82062)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="xwn2jnbkx"/><stop offset="1" class="o70hz4bsj"/></radialGradient><radialGradient id="iouQj6d" cx="0" cy="0" r="1" gradientTransform="rotate(-106.955 16.847 5.586)scale(12.992 7.29952)" gradientUnits="userSpaceOnUse"><stop class="vuekx_bhg"/><stop offset="1" class="ufq42fb7e"/></radialGradient><radialGradient id="i5zZIsW" cx="0" cy="0" r="1" gradientTransform="matrix(-10.15397 6.59255 -7.36397 -11.34211 28.314 17.192)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="dkaaooa7z"/><stop offset="1" class="q8r289j7a"/></radialGradient><radialGradient id="iowq3gc" cx="0" cy="0" r="1" gradientTransform="rotate(147.319 1.535 11.554)scale(9.543 11.6289)" gradientUnits="userSpaceOnUse"><stop class="dkaaooa7z"/><stop offset=".696" class="q8r289j7a"/></radialGradient><radialGradient id="iiEt9yc" cx="0" cy="0" r="1" gradientTransform="matrix(2.50063 7.6534 -2.85323 .93225 11.264 16.434)" gradientUnits="userSpaceOnUse"><stop class="dkaaooa7z"/><stop offset="1" class="q8r289j7a"/></radialGradient><filter id="i71xvwe" width="16.26" height="16.26" x="3.706" y="6.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.47451 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_15000"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_15000" result="shape"/></filter><filter id="iehzpeL" width="27.941" height="17.964" x="2" y="12.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.698039 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15000"/></filter><filter id="iz03Vfe" width="27.941" height="17.964" x="2" y="12.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.698039 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15000"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.698039 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_15000" result="effect2_innerShadow_18_15000"/></filter><linearGradient id="ivrj1xd" x1="18.217" x2="7.029" y1="7.467" y2="21.741" gradientUnits="userSpaceOnUse"><stop class="s91ts3bpo"/><stop offset="1" class="uc7451bcz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sun-behind-cloud" /></template>
<style>
.a_xm9geyk {
  stop-color: var(--svg-color--f0851d, #F0851D);
  stop-opacity: 0;
}

.aksdkybif {
  stop-color: var(--svg-color--dca225, #DCA225);
}

.chsd9qafy {
  stop-color: var(--svg-color--dca225, #DCA225);
  stop-opacity: 0;
}

.dkaaooa7z {
  stop-color: var(--svg-color--f2f0ff, #F2F0FF);
}

.e82rysb7i {
  fill: var(--svg-color--e0d3ff, #E0D3FF);
  d: path("M27.24 14.59c-3.55-3.46-9.23-3.4-12.69.15a8.95 8.95 0 0 0-2.016 3.201a.268.268 0 0 1-.399.13a6 6 0 0 0-.985-.531A6.457 6.457 0 0 0 2 23.41c0 1.52.53 2.92 1.41 4.03A6.48 6.48 0 0 0 8.58 30h12.69c2.82 0 5.31-1.39 6.83-3.52c2.72-3.56 2.42-8.68-.86-11.89");
}

.ft5dv1b6b {
  fill: none;
}

.gsrhrkoli {
  stop-color: var(--svg-color--ff942a, #FF942A);
  stop-opacity: 0;
}

.hemkrl1wk {
  stop-color: var(--svg-color--dca21c, #DCA21C);
}

.j756vz6_d {
  stop-color: var(--svg-color--d89a29, #D89A29);
}

.ku2pfdbii {
  stop-color: var(--svg-color--ffa13d, #FFA13D);
  stop-opacity: 0;
}

.kypg0578v {
  stop-color: var(--svg-color--e0762a, #E0762A);
}

.mlwsi7b0o {
  stop-color: var(--svg-color--ffd13d, #FFD13D);
}

.mulvig9sp {
  stop-color: var(--svg-color--f0851d, #F0851D);
}

.nh9jgyb1q {
  stop-color: var(--svg-color--b7b6fa, #B7B6FA);
}

.o70hz4bsj {
  stop-color: var(--svg-color--b8b7ff, #B8B7FF);
  stop-opacity: 0;
}

.pud-xubcs {
  stop-color: var(--svg-color--ffa13d, #FFA13D);
}

.q3m8m7bhy {
  stop-color: var(--svg-color--ffa13a, #FFA13A);
}

.q8r289j7a {
  stop-color: var(--svg-color--f2f0ff, #F2F0FF);
  stop-opacity: 0;
}

.r02t0tqck {
  stop-color: var(--svg-color--cecdff, #CECDFF);
}

.rwhrj1bde {
  stop-color: var(--svg-color--e3745b, #E3745B);
}

.s91ts3bpo {
  stop-color: var(--svg-color--fc8b23, #FC8B23);
}

.tdsz55bit {
  d: path("M12.136 22.093a7.83 7.83 0 1 0 0-15.66a7.83 7.83 0 0 0 0 15.66");
}

.tzt2apygr {
  stop-color: var(--svg-color--e3745b, #E3745B);
  stop-opacity: 0;
}

.uc7451bcz {
  stop-color: var(--svg-color--e67639, #E67639);
}

.ufq42fb7e {
  stop-color: var(--svg-color--d6ccff, #D6CCFF);
  stop-opacity: 0;
}

.uhy_-rb7u {
  stop-color: var(--svg-color--ff942a, #FF942A);
}

.vuekx_bhg {
  stop-color: var(--svg-color--d6ccff, #D6CCFF);
}

.vxrp39aul {
  stop-color: var(--svg-color--ffa13a, #FFA13A);
  stop-opacity: 0;
}

.xwn2jnbkx {
  stop-color: var(--svg-color--b8b7ff, #B8B7FF);
}

.yblikdbdb {
  d: path("M27.24 14.59c-3.55-3.46-9.23-3.4-12.69.15a8.95 8.95 0 0 0-2.016 3.201a.268.268 0 0 1-.399.13a6 6 0 0 0-.985-.531A6.457 6.457 0 0 0 2 23.41c0 1.52.53 2.92 1.41 4.03A6.48 6.48 0 0 0 8.58 30h12.69c2.82 0 5.31-1.39 6.83-3.52c2.72-3.56 2.42-8.68-.86-11.89");
}

.yiqe49k2f {
  stop-color: var(--svg-color--e0762a, #E0762A);
  stop-opacity: 0;
}

.ysji-m2pv {
  d: path("M12.26 22.68a4.04 4.04 0 1 0 0-8.08a4.04 4.04 0 0 0 0 8.08");
}

.zo_jqkdbv {
  d: path("M10.325 4.89c1.116-1.256 2.634-1.056 3.605 0l.592.686a.98.98 0 0 0 .803.313l1.053-.313c1.435-.308 2.739.763 2.739 2.425v.627c.03.341.329.573.637.724l.951.397c1.376.672 1.72 2.266.718 3.605l-.285.375c-.255.346-.203.799.051 1.145l.285.399c1.037 1.275.452 3.025-1.012 3.636l-.818.342c-.309.129-.43.35-.487.68L19.1 21a2.267 2.267 0 0 1-2.551 1.984l-1.247-.333c-.3-.042-.672.057-.871.37l-.45.615c-1.116 1.258-2.623 1.05-3.382.313l-.83-1.005c-.218-.21-.491-.39-.82-.266l-1.254.343c-1.037.147-2.257-.65-2.452-1.678l-.145-1.488a.98.98 0 0 0-.549-.705l-.88-.303c-1.324-.617-1.767-2.11-1.007-3.357l.496-.687a.98.98 0 0 0-.024-1.058l-.37-.523c-1.048-1.492-.324-3.16 1.229-3.66l.342-.11c.378-.122.743-.435.775-.831l.076-.96c.124-1.56 1.547-2.455 3.043-2l.485.147c.467.182.833.027 1.087-.25z");
}

</style>
