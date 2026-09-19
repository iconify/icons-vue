<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ia39m6d)"><path class="smkt-zb3q"/><path fill="url(#iFgn6Md)" class="aecp66gxq"/></g><path fill="url(#iI0TEid)" class="aecp66gxq"/><path fill="url(#i3Egc5b)" class="aecp66gxq"/><path fill="url(#i2IXxBm)" class="aecp66gxq"/><path fill="url(#iytPB4b)" class="aecp66gxq"/><path fill="url(#ibZ8nCe)" class="aecp66gxq"/><path fill="url(#ilUnSoc)" class="aecp66gxq"/><g filter="url(#ifJgalD)" class="p9_4sib0u"><path class="b2_q-ebsi"/><path class="zkas7jbkv"/><path class="se36js6jc"/></g><path class="wd4ucb7il"/><path fill="url(#iEN4rvb)" class="lj85eob5n"/><path fill="url(#iY3RCmc)" class="lj85eob5n"/><path fill="url(#iQxGnie)" class="lj85eob5n"/><path fill="url(#iqizQkc)" class="lj85eob5n"/><g filter="url(#i6J9MOc)"><rect class="zqel64bjb"/></g><path class="r9ynpbc3w"/><path fill="url(#i8RHyLb)" class="efifp5hhq"/><path fill="url(#iU18OBe)" class="efifp5hhq"/><path fill="url(#iNm8KEK)" class="efifp5hhq"/><g filter="url(#iHpfyPb)"><rect class="v31h_nb-s"/></g><path class="jbbgm733b"/><path fill="url(#i0hBkzt)" class="nvj_rgbeb"/><path fill="url(#iBJofSX)" class="nvj_rgbeb"/><path fill="url(#iC2BHJM)" class="nvj_rgbeb"/><path fill="url(#i4Zwd3d)" class="mt39rwc2u"/><path fill="url(#iQ6NJIe)" class="mt39rwc2u"/><path fill="url(#iSS7skb)" class="mt39rwc2u"/><defs><radialGradient id="iFgn6Md" cx="0" cy="0" r="1" gradientTransform="rotate(138.108 7.776 13.246)scale(14.0119 10.4377)" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></radialGradient><radialGradient id="iI0TEid" cx="0" cy="0" r="1" gradientTransform="rotate(-123.041 15.084 -1.596)scale(2.55392 2.71595)" gradientUnits="userSpaceOnUse"><stop class="uwwvugbwq"/><stop offset="1" class="hxkkado1p"/></radialGradient><radialGradient id="i3Egc5b" cx="0" cy="0" r="1" gradientTransform="rotate(70.346 9.217 17.077)scale(5.07426 17.3147)" gradientUnits="userSpaceOnUse"><stop class="wyj2c0peu"/><stop offset="1" class="tx-xnn8qh"/></radialGradient><radialGradient id="i2IXxBm" cx="0" cy="0" r="1" gradientTransform="rotate(153.85 12.615 6.398)scale(2.56455 2.04967)" gradientUnits="userSpaceOnUse"><stop class="ngf665bqr"/><stop offset="1" class="xvjkibwmm"/></radialGradient><radialGradient id="iytPB4b" cx="0" cy="0" r="1" gradientTransform="matrix(1.61753 1.77534 -9.13543 8.3234 18.598 5.403)" gradientUnits="userSpaceOnUse"><stop class="uqj3dfp2c"/><stop offset="1" class="p1-gnab4p"/></radialGradient><radialGradient id="ibZ8nCe" cx="0" cy="0" r="1" gradientTransform="matrix(1.14411 0 0 3.35343 17.611 8.48)" gradientUnits="userSpaceOnUse"><stop class="n92y72btt"/><stop offset="1" class="c2jgz5l9i"/></radialGradient><radialGradient id="ilUnSoc" cx="0" cy="0" r="1" gradientTransform="matrix(-23.07864 10.46505 -10.22957 -22.55934 27.226 13.478)" gradientUnits="userSpaceOnUse"><stop offset=".927" class="xia3e6b3v"/><stop offset="1" class="o5lciubfk"/></radialGradient><radialGradient id="iY3RCmc" cx="0" cy="0" r="1" gradientTransform="matrix(4.61755 5.37902 -4.6731 4.01156 3.132 9.113)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="kl9idebuj"/><stop offset="1" class="dkfejtb3h"/></radialGradient><radialGradient id="iQxGnie" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.74306 -1.49874 0 6.484 11.534)" gradientUnits="userSpaceOnUse"><stop class="gimt_wbus"/><stop offset="1" class="hvweefb6x"/></radialGradient><radialGradient id="iU18OBe" cx="0" cy="0" r="1" gradientTransform="matrix(4.49973 6.05545 -5.09585 3.78666 7.922 8.458)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="kl9idebuj"/><stop offset="1" class="dkfejtb3h"/></radialGradient><radialGradient id="iNm8KEK" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.21375 -1.4605 0 11.188 11.184)" gradientUnits="userSpaceOnUse"><stop class="gimt_wbus"/><stop offset="1" class="hvweefb6x"/></radialGradient><radialGradient id="iBJofSX" cx="0" cy="0" r="1" gradientTransform="rotate(53.002 -1.933 17.018)scale(7.59535 6.41688)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="kl9idebuj"/><stop offset="1" class="dkfejtb3h"/></radialGradient><radialGradient id="iC2BHJM" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.24545 -2.82329 0 16.55 8.585)" gradientUnits="userSpaceOnUse"><stop class="lhdtgybwx"/><stop offset="1" class="fycqk15mq"/></radialGradient><radialGradient id="i4Zwd3d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45056 7.51928 -4.3011 -1.40174 23.97 12.268)" gradientUnits="userSpaceOnUse"><stop class="u3grpac7u"/><stop offset="1" class="srdpl700n"/></radialGradient><radialGradient id="iQ6NJIe" cx="0" cy="0" r="1" gradientTransform="rotate(146.043 12.264 11.645)scale(3.52755 4.3626)" gradientUnits="userSpaceOnUse"><stop class="xubb47nuq"/><stop offset="1" class="ls1ikzt2f"/></radialGradient><radialGradient id="iSS7skb" cx="0" cy="0" r="1" gradientTransform="matrix(1.1188 .37926 -2.2621 6.67318 22.105 16.363)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="q_15s7zom"/><stop offset="1" class="qsl0x4f9y"/></radialGradient><linearGradient id="iEN4rvb" x1="3.103" x2="5.926" y1="12.505" y2="12.505" gradientUnits="userSpaceOnUse"><stop class="fpq8_5cll"/><stop offset="1" class="ksgnyzgnh"/></linearGradient><linearGradient id="iqizQkc" x1="2.43" x2="3.039" y1="11.534" y2="11.534" gradientUnits="userSpaceOnUse"><stop class="fhfpibfds"/><stop offset="1" class="f6d5cbbzn"/></linearGradient><linearGradient id="i8RHyLb" x1="7.893" x2="10.645" y1="12.277" y2="12.277" gradientUnits="userSpaceOnUse"><stop class="fpq8_5cll"/><stop offset="1" class="ksgnyzgnh"/></linearGradient><linearGradient id="i0hBkzt" x1="12.792" x2="15.587" y1="12.148" y2="12.148" gradientUnits="userSpaceOnUse"><stop class="fpq8_5cll"/><stop offset="1" class="ksgnyzgnh"/></linearGradient><filter id="ia39m6d" width="27.675" height="25.549" x="2.538" y="3.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.490196 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2013"/></filter><filter id="ifJgalD" width="16.091" height="12.26" x="1.909" y="6.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2013" stdDeviation="1"/></filter><filter id="i6J9MOc" width="2.266" height="8.313" x="6.249" y="7.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2013" stdDeviation=".375"/></filter><filter id="iHpfyPb" width="2.266" height="8.719" x="11.186" y="6.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2013" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pinching-hand-light" /></template>
<style>
.aecp66gxq {
  d: path("M28.92 14.188c-.962-1.437-2.828-1.782-4.375-.438c-.76.661-1.648 1.618-1.648.464v-3.097c.07-1.281.828-1.625 2.063-1.203c1.756.445 3.168-.964 3.43-2.164c.203-.938-.008-2.441-1.61-3.203c-3.297-1.422-7.36-.203-8.9 3.333l-3.302 2.334H2.538v6.583c0 7.719 3.982 12.219 10.456 12.219c3.26 0 5.55-1.252 8.003-3.452c1.31-1.174 2.412-2.397 4.22-4.08c2.032-2.218 5.61-4.453 3.704-7.297");
}

.b2_q-ebsi {
  d: path("M13.338 8.953a2.656 2.656 0 0 0-2.662 2.643v2.974c0 1.457 1.194 2.643 2.662 2.643S16 16.027 16 14.57v-2.974a2.65 2.65 0 0 0-2.662-2.643");
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.c2jgz5l9i {
  stop-color: var(--svg-color--e69d77, #E69D77);
  stop-opacity: 0;
}

.dkfejtb3h {
  stop-color: var(--svg-color--c78887, #C78887);
}

.efifp5hhq {
  d: path("M10.18 6.156c-1.565 0-2.838 1.23-2.838 2.744v4.569c0 1.512 1.273 2.743 2.838 2.743s2.838-1.23 2.838-2.743v-4.58c0-1.512-1.273-2.733-2.838-2.733");
}

.f6d5cbbzn {
  stop-color: var(--svg-color--f0b69b, #F0B69B);
  stop-opacity: 0;
}

.fhfpibfds {
  stop-color: var(--svg-color--f0b69b, #F0B69B);
}

.fpq8_5cll {
  stop-color: var(--svg-color--e0ab92, #E0AB92);
}

.ft5dv1b6b {
  fill: none;
}

.fycqk15mq {
  stop-color: var(--svg-color--ffe7c8, #FFE7C8);
  stop-opacity: 0;
}

.gimt_wbus {
  stop-color: var(--svg-color--f4c1b0, #F4C1B0);
}

.hvweefb6x {
  stop-color: var(--svg-color--f4c1b0, #F4C1B0);
  stop-opacity: 0;
}

.hxkkado1p {
  stop-color: var(--svg-color--cf8d8a, #CF8D8A);
  stop-opacity: 0;
}

.jbbgm733b {
  fill: var(--svg-color--facbb5, #FACBB5);
  d: path("M15.116 6.016c-1.59 0-2.883 1.284-2.883 2.862v4.349c0 1.578 1.294 2.862 2.883 2.862s2.883-1.284 2.883-2.862v-4.35a2.87 2.87 0 0 0-2.883-2.861");
}

.kl9idebuj {
  stop-color: var(--svg-color--c78887, #C78887);
  stop-opacity: 0;
}

.ksgnyzgnh {
  stop-color: var(--svg-color--e0ab92, #E0AB92);
  stop-opacity: 0;
}

.lhdtgybwx {
  stop-color: var(--svg-color--ffe7c8, #FFE7C8);
}

.lj85eob5n {
  d: path("M5.45 7.068c-1.606 0-2.912 1.19-2.912 2.655v3.622C2.538 14.809 3.844 16 5.45 16s2.912-1.191 2.912-2.655V9.723c0-1.464-1.306-2.655-2.912-2.655");
}

.ls1ikzt2f {
  stop-color: var(--svg-color--ffe5c7, #FFE5C7);
  stop-opacity: 0;
}

.mt39rwc2u {
  d: path("M24.546 13.75c1.546-1.344 3.412-.999 4.375.438c1.525 2.275-.461 4.16-2.356 5.96a28 28 0 0 0-1.348 1.336c-.884.823-1.6 1.536-2.253 2.187a52 52 0 0 1-1.967 1.893c-.446.4-.886.769-1.328 1.104l3.427-11.924c.252.078.71-.333 1.167-.743z");
}

.n92y72btt {
  stop-color: var(--svg-color--e69d77, #E69D77);
}

.ngf665bqr {
  stop-color: var(--svg-color--ffe3c7, #FFE3C7);
}

.nvj_rgbeb {
  d: path("M15.116 6.016c-1.59 0-2.883 1.284-2.883 2.862v4.349c0 1.578 1.294 2.862 2.883 2.862s2.883-1.284 2.883-2.862v-4.35a2.87 2.87 0 0 0-2.883-2.861");
}

.o5lciubfk {
  stop-color: var(--svg-color--eeb29c, #EEB29C);
}

.p1-gnab4p {
  stop-color: var(--svg-color--d8a68a, #D8A68A);
  stop-opacity: 0;
}

.p9_4sib0u {
  fill: var(--svg-color--a9645b, #A9645B);
}

.q_15s7zom {
  stop-color: var(--svg-color--ffd6be, #FFD6BE);
}

.qsl0x4f9y {
  stop-color: var(--svg-color--ffd6be, #FFD6BE);
  stop-opacity: 0;
}

.r9ynpbc3w {
  fill: var(--svg-color--facbb5, #FACBB5);
  d: path("M10.18 6.156c-1.565 0-2.838 1.23-2.838 2.744v4.569c0 1.512 1.273 2.743 2.838 2.743s2.838-1.23 2.838-2.743v-4.58c0-1.512-1.273-2.733-2.838-2.733");
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.se36js6jc {
  d: path("M6.192 9.542a2.28 2.28 0 0 0-2.283 2.266v2.55a2.28 2.28 0 0 0 2.283 2.267a2.28 2.28 0 0 0 2.282-2.267v-2.55a2.273 2.273 0 0 0-2.282-2.266");
}

.smkt-zb3q {
  fill: var(--svg-color--f4bdae, #F4BDAE);
  d: path("M28.92 14.188c-.962-1.437-2.828-1.782-4.375-.438c-.76.661-1.648 1.618-1.648.464v-3.097c.07-1.281.828-1.625 2.063-1.203c1.756.445 3.168-.964 3.43-2.164c.203-.938-.008-2.441-1.61-3.203c-3.297-1.422-7.36-.203-8.9 3.333l-3.302 2.334H2.538v6.583c0 7.719 3.982 12.219 10.456 12.219c3.26 0 5.55-1.252 8.003-3.452c1.31-1.174 2.412-2.397 4.22-4.08c2.032-2.218 5.61-4.453 3.704-7.297");
}

.srdpl700n {
  stop-color: var(--svg-color--e4a686, #E4A686);
  stop-opacity: 0;
}

.tx-xnn8qh {
  stop-color: var(--svg-color--f1c2a5, #F1C2A5);
  stop-opacity: 0;
}

.u3grpac7u {
  stop-color: var(--svg-color--e4a686, #E4A686);
}

.uqj3dfp2c {
  stop-color: var(--svg-color--d8a68a, #D8A68A);
}

.uwwvugbwq {
  stop-color: var(--svg-color--cf8d8a, #CF8D8A);
}

.v31h_nb-s {
  width: 0.766px;
  height: 7.219px;
  x: 11.936px;
  y: 7.625px;
  fill: var(--svg-color--da9f7c, #DA9F7C);
  rx: 0.383px;
}

.wd4ucb7il {
  fill: var(--svg-color--facbb5, #FACBB5);
  d: path("M5.45 7.068c-1.606 0-2.912 1.19-2.912 2.655v3.622C2.538 14.809 3.844 16 5.45 16s2.912-1.191 2.912-2.655V9.723c0-1.464-1.306-2.655-2.912-2.655");
}

.wyj2c0peu {
  stop-color: var(--svg-color--f1c2a5, #F1C2A5);
}

.xia3e6b3v {
  stop-color: var(--svg-color--eeb29c, #EEB29C);
  stop-opacity: 0;
}

.xubb47nuq {
  stop-color: var(--svg-color--ffe5c7, #FFE5C7);
}

.xvjkibwmm {
  stop-color: var(--svg-color--ffe3c7, #FFE3C7);
  stop-opacity: 0;
}

.zkas7jbkv {
  d: path("M9.53 9.357A2.527 2.527 0 0 0 7 11.87v2.828a2.527 2.527 0 0 0 2.532 2.514a2.526 2.526 0 0 0 2.532-2.514V11.87A2.52 2.52 0 0 0 9.53 9.357");
}

.zqel64bjb {
  width: 0.766px;
  height: 6.813px;
  x: 6.999px;
  y: 8.031px;
  fill: var(--svg-color--da9f7c, #DA9F7C);
  rx: 0.383px;
}

</style>
