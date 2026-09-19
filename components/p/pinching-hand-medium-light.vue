<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iKbjDLe)"><path class="ns5s2ubym"/><path fill="url(#ijmH2bb)" class="aecp66gxq"/></g><path fill="url(#inRCmyZ)" class="aecp66gxq"/><path fill="url(#izIBvSc)" class="aecp66gxq"/><path fill="url(#iQwzfZc)" class="aecp66gxq"/><path fill="url(#ideMmqd)" class="aecp66gxq"/><path fill="url(#iiBsiJb)" class="aecp66gxq"/><path fill="url(#iyDlDFN)" class="aecp66gxq"/><g filter="url(#i8hIdId)" class="mb40uqbnj"><path class="b2_q-ebsi"/><path class="zkas7jbkv"/><path class="se36js6jc"/></g><path class="u61kppbun"/><path fill="url(#iWSFy0h)" class="lj85eob5n"/><path fill="url(#iJOtOwc)" class="lj85eob5n"/><path fill="url(#iOyLPfb)" class="lj85eob5n"/><path fill="url(#isOZqbd)" class="lj85eob5n"/><g filter="url(#ipdasre)"><rect class="wep8zeiqj"/></g><path class="ce82_jbzk"/><path fill="url(#i7AqQhT)" class="efifp5hhq"/><path fill="url(#ioyi6Wu)" class="efifp5hhq"/><path fill="url(#izCtIlc)" class="efifp5hhq"/><g filter="url(#i0HxVpc)"><rect class="etqs9obzv"/></g><path class="jn76mrb5a"/><path fill="url(#iyKMq1S)" class="nvj_rgbeb"/><path fill="url(#iqkDPyc)" class="nvj_rgbeb"/><path fill="url(#ilYCwqE)" class="nvj_rgbeb"/><path fill="url(#iuTuMGu)" class="mt39rwc2u"/><path fill="url(#ibBgmyc)" class="mt39rwc2u"/><path fill="url(#id5H8Uc)" class="mt39rwc2u"/><defs><radialGradient id="ijmH2bb" cx="0" cy="0" r="1" gradientTransform="rotate(138.108 7.776 13.246)scale(14.0119 10.4377)" gradientUnits="userSpaceOnUse"><stop class="c-t584bua"/><stop offset="1" class="oexw0abgw"/></radialGradient><radialGradient id="inRCmyZ" cx="0" cy="0" r="1" gradientTransform="rotate(-123.041 15.084 -1.596)scale(2.55392 2.71595)" gradientUnits="userSpaceOnUse"><stop class="rjz-jn1yt"/><stop offset="1" class="hcgrq_30v"/></radialGradient><radialGradient id="izIBvSc" cx="0" cy="0" r="1" gradientTransform="rotate(70.346 9.217 17.077)scale(5.07426 17.3147)" gradientUnits="userSpaceOnUse"><stop class="bdyjx2bco"/><stop offset="1" class="j9p1jnbuf"/></radialGradient><radialGradient id="iQwzfZc" cx="0" cy="0" r="1" gradientTransform="rotate(153.85 12.615 6.398)scale(2.56455 2.04967)" gradientUnits="userSpaceOnUse"><stop class="icjbfbcsz"/><stop offset="1" class="l9j77zbpn"/></radialGradient><radialGradient id="ideMmqd" cx="0" cy="0" r="1" gradientTransform="matrix(1.61753 1.77534 -9.13543 8.3234 18.598 5.403)" gradientUnits="userSpaceOnUse"><stop class="rh0nzu15o"/><stop offset="1" class="h-6qxcchr"/></radialGradient><radialGradient id="iiBsiJb" cx="0" cy="0" r="1" gradientTransform="matrix(1.14411 0 0 3.35343 17.611 8.48)" gradientUnits="userSpaceOnUse"><stop class="mg19yhb2s"/><stop offset="1" class="tzhk5r8ib"/></radialGradient><radialGradient id="iyDlDFN" cx="0" cy="0" r="1" gradientTransform="matrix(-23.07864 10.46505 -10.22957 -22.55934 27.226 13.478)" gradientUnits="userSpaceOnUse"><stop offset=".927" class="g0v90brwv"/><stop offset="1" class="ic9qs4bvm"/></radialGradient><radialGradient id="iJOtOwc" cx="0" cy="0" r="1" gradientTransform="matrix(4.61755 5.37902 -4.6731 4.01156 3.132 9.113)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="l0j_xf7zq"/><stop offset="1" class="ceok2bc3l"/></radialGradient><radialGradient id="iOyLPfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.74306 -1.49874 0 6.484 11.534)" gradientUnits="userSpaceOnUse"><stop class="ywxfzflgg"/><stop offset="1" class="t_a7nrbzn"/></radialGradient><radialGradient id="ioyi6Wu" cx="0" cy="0" r="1" gradientTransform="matrix(4.49973 6.05545 -5.09585 3.78666 7.922 8.458)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="l0j_xf7zq"/><stop offset="1" class="ceok2bc3l"/></radialGradient><radialGradient id="izCtIlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.21375 -1.4605 0 11.188 11.184)" gradientUnits="userSpaceOnUse"><stop class="ywxfzflgg"/><stop offset="1" class="t_a7nrbzn"/></radialGradient><radialGradient id="iqkDPyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8739 -7.49705 0 15.116 7.215)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="l0j_xf7zq"/><stop offset="1" class="ceok2bc3l"/></radialGradient><radialGradient id="ilYCwqE" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.0117 -2.44401 0 16.139 8.262)" gradientUnits="userSpaceOnUse"><stop class="ktzs-abxm"/><stop offset="1" class="f-v3r2bzo"/></radialGradient><radialGradient id="iuTuMGu" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45056 7.51928 -4.3011 -1.40174 23.97 12.268)" gradientUnits="userSpaceOnUse"><stop class="wpwq_uh8n"/><stop offset="1" class="kcyx-abcf"/></radialGradient><radialGradient id="ibBgmyc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.7342 1.76829 -1.38594 -2.14299 28.75 14.656)" gradientUnits="userSpaceOnUse"><stop class="ca8jlyb5t"/><stop offset="1" class="lrtkjiyby"/></radialGradient><radialGradient id="id5H8Uc" cx="0" cy="0" r="1" gradientTransform="matrix(1.1188 .37926 -2.2621 6.67318 22.105 16.363)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="e-6s3mb8z"/><stop offset="1" class="jdlqgybli"/></radialGradient><linearGradient id="iWSFy0h" x1="3.103" x2="5.926" y1="12.505" y2="12.505" gradientUnits="userSpaceOnUse"><stop class="wvnig9s-p"/><stop offset="1" class="gkzgrvf5v"/></linearGradient><linearGradient id="isOZqbd" x1="2.43" x2="3.039" y1="11.534" y2="11.534" gradientUnits="userSpaceOnUse"><stop class="q5_tafbih"/><stop offset="1" class="c7jfa1b0v"/></linearGradient><linearGradient id="i7AqQhT" x1="7.893" x2="10.645" y1="12.277" y2="12.277" gradientUnits="userSpaceOnUse"><stop class="wvnig9s-p"/><stop offset="1" class="gkzgrvf5v"/></linearGradient><linearGradient id="iyKMq1S" x1="12.792" x2="15.587" y1="12.148" y2="12.148" gradientUnits="userSpaceOnUse"><stop class="wvnig9s-p"/><stop offset="1" class="gkzgrvf5v"/></linearGradient><filter id="iKbjDLe" width="27.675" height="25.549" x="2.538" y="3.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.443137 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2003"/></filter><filter id="i8hIdId" width="16.091" height="12.26" x="1.909" y="6.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2003" stdDeviation="1"/></filter><filter id="ipdasre" width="2.266" height="8.313" x="6.249" y="7.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2003" stdDeviation=".375"/></filter><filter id="i0HxVpc" width="2.266" height="8.719" x="11.186" y="6.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2003" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pinching-hand-medium-light" /></template>
<style>
.aecp66gxq {
  d: path("M28.92 14.188c-.962-1.437-2.828-1.782-4.375-.438c-.76.661-1.648 1.618-1.648.464v-3.097c.07-1.281.828-1.625 2.063-1.203c1.756.445 3.168-.964 3.43-2.164c.203-.938-.008-2.441-1.61-3.203c-3.297-1.422-7.36-.203-8.9 3.333l-3.302 2.334H2.538v6.583c0 7.719 3.982 12.219 10.456 12.219c3.26 0 5.55-1.252 8.003-3.452c1.31-1.174 2.412-2.397 4.22-4.08c2.032-2.218 5.61-4.453 3.704-7.297");
}

.b2_q-ebsi {
  d: path("M13.338 8.953a2.656 2.656 0 0 0-2.662 2.643v2.974c0 1.457 1.194 2.643 2.662 2.643S16 16.027 16 14.57v-2.974a2.65 2.65 0 0 0-2.662-2.643");
}

.bdyjx2bco {
  stop-color: var(--svg-color--e6b790, #E6B790);
}

.c-t584bua {
  stop-color: var(--svg-color--fec8a5, #FEC8A5);
}

.c7jfa1b0v {
  stop-color: var(--svg-color--dea788, #DEA788);
  stop-opacity: 0;
}

.ca8jlyb5t {
  stop-color: var(--svg-color--ffcfa9, #FFCFA9);
}

.ce82_jbzk {
  fill: var(--svg-color--e0aa8b, #E0AA8B);
  d: path("M10.18 6.156c-1.565 0-2.838 1.23-2.838 2.744v4.569c0 1.512 1.273 2.743 2.838 2.743s2.838-1.23 2.838-2.743v-4.58c0-1.512-1.273-2.733-2.838-2.733");
}

.ceok2bc3l {
  stop-color: var(--svg-color--bb7b7d, #BB7B7D);
}

.e-6s3mb8z {
  stop-color: var(--svg-color--f4bc9c, #F4BC9C);
}

.efifp5hhq {
  d: path("M10.18 6.156c-1.565 0-2.838 1.23-2.838 2.744v4.569c0 1.512 1.273 2.743 2.838 2.743s2.838-1.23 2.838-2.743v-4.58c0-1.512-1.273-2.733-2.838-2.733");
}

.etqs9obzv {
  width: 0.766px;
  height: 7.219px;
  x: 11.936px;
  y: 7.625px;
  fill: var(--svg-color--c2885e, #C2885E);
  rx: 0.383px;
}

.f-v3r2bzo {
  stop-color: var(--svg-color--ffcda2, #FFCDA2);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0v90brwv {
  stop-color: var(--svg-color--dc9f89, #DC9F89);
  stop-opacity: 0;
}

.gkzgrvf5v {
  stop-color: var(--svg-color--cf9d78, #CF9D78);
  stop-opacity: 0;
}

.h-6qxcchr {
  stop-color: var(--svg-color--c39574, #C39574);
  stop-opacity: 0;
}

.hcgrq_30v {
  stop-color: var(--svg-color--bd7a7d, #BD7A7D);
  stop-opacity: 0;
}

.ic9qs4bvm {
  stop-color: var(--svg-color--dc9f89, #DC9F89);
}

.icjbfbcsz {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
}

.j9p1jnbuf {
  stop-color: var(--svg-color--e6b790, #E6B790);
  stop-opacity: 0;
}

.jdlqgybli {
  stop-color: var(--svg-color--f4bc9c, #F4BC9C);
  stop-opacity: 0;
}

.jn76mrb5a {
  fill: var(--svg-color--e0aa8b, #E0AA8B);
  d: path("M15.116 6.016c-1.59 0-2.883 1.284-2.883 2.862v4.349c0 1.578 1.294 2.862 2.883 2.862s2.883-1.284 2.883-2.862v-4.35a2.87 2.87 0 0 0-2.883-2.861");
}

.kcyx-abcf {
  stop-color: var(--svg-color--cb8f69, #CB8F69);
  stop-opacity: 0;
}

.ktzs-abxm {
  stop-color: var(--svg-color--ffcda2, #FFCDA2);
}

.l0j_xf7zq {
  stop-color: var(--svg-color--bb7b7d, #BB7B7D);
  stop-opacity: 0;
}

.l9j77zbpn {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
  stop-opacity: 0;
}

.lj85eob5n {
  d: path("M5.45 7.068c-1.606 0-2.912 1.19-2.912 2.655v3.622C2.538 14.809 3.844 16 5.45 16s2.912-1.191 2.912-2.655V9.723c0-1.464-1.306-2.655-2.912-2.655");
}

.lrtkjiyby {
  stop-color: var(--svg-color--ffcfa9, #FFCFA9);
  stop-opacity: 0;
}

.mb40uqbnj {
  fill: var(--svg-color--93534f, #93534F);
}

.mg19yhb2s {
  stop-color: var(--svg-color--c58256, #C58256);
}

.mt39rwc2u {
  d: path("M24.546 13.75c1.546-1.344 3.412-.999 4.375.438c1.525 2.275-.461 4.16-2.356 5.96a28 28 0 0 0-1.348 1.336c-.884.823-1.6 1.536-2.253 2.187a52 52 0 0 1-1.967 1.893c-.446.4-.886.769-1.328 1.104l3.427-11.924c.252.078.71-.333 1.167-.743z");
}

.ns5s2ubym {
  fill: var(--svg-color--e5ab95, #E5AB95);
  d: path("M28.92 14.188c-.962-1.437-2.828-1.782-4.375-.438c-.76.661-1.648 1.618-1.648.464v-3.097c.07-1.281.828-1.625 2.063-1.203c1.756.445 3.168-.964 3.43-2.164c.203-.938-.008-2.441-1.61-3.203c-3.297-1.422-7.36-.203-8.9 3.333l-3.302 2.334H2.538v6.583c0 7.719 3.982 12.219 10.456 12.219c3.26 0 5.55-1.252 8.003-3.452c1.31-1.174 2.412-2.397 4.22-4.08c2.032-2.218 5.61-4.453 3.704-7.297");
}

.nvj_rgbeb {
  d: path("M15.116 6.016c-1.59 0-2.883 1.284-2.883 2.862v4.349c0 1.578 1.294 2.862 2.883 2.862s2.883-1.284 2.883-2.862v-4.35a2.87 2.87 0 0 0-2.883-2.861");
}

.oexw0abgw {
  stop-color: var(--svg-color--fec8a5, #FEC8A5);
  stop-opacity: 0;
}

.q5_tafbih {
  stop-color: var(--svg-color--dea788, #DEA788);
}

.rh0nzu15o {
  stop-color: var(--svg-color--c39574, #C39574);
}

.rjz-jn1yt {
  stop-color: var(--svg-color--bd7a7d, #BD7A7D);
}

.se36js6jc {
  d: path("M6.192 9.542a2.28 2.28 0 0 0-2.283 2.266v2.55a2.28 2.28 0 0 0 2.283 2.267a2.28 2.28 0 0 0 2.282-2.267v-2.55a2.273 2.273 0 0 0-2.282-2.266");
}

.t_a7nrbzn {
  stop-color: var(--svg-color--e2b197, #E2B197);
  stop-opacity: 0;
}

.tzhk5r8ib {
  stop-color: var(--svg-color--c58256, #C58256);
  stop-opacity: 0;
}

.u61kppbun {
  fill: var(--svg-color--e0aa8b, #E0AA8B);
  d: path("M5.45 7.068c-1.606 0-2.912 1.19-2.912 2.655v3.622C2.538 14.809 3.844 16 5.45 16s2.912-1.191 2.912-2.655V9.723c0-1.464-1.306-2.655-2.912-2.655");
}

.wep8zeiqj {
  width: 0.766px;
  height: 6.813px;
  x: 6.999px;
  y: 8.031px;
  fill: var(--svg-color--c2885e, #C2885E);
  rx: 0.383px;
}

.wpwq_uh8n {
  stop-color: var(--svg-color--cb8f69, #CB8F69);
}

.wvnig9s-p {
  stop-color: var(--svg-color--cf9d78, #CF9D78);
}

.ywxfzflgg {
  stop-color: var(--svg-color--e2b197, #E2B197);
}

.zkas7jbkv {
  d: path("M9.53 9.357A2.527 2.527 0 0 0 7 11.87v2.828a2.527 2.527 0 0 0 2.532 2.514a2.526 2.526 0 0 0 2.532-2.514V11.87A2.52 2.52 0 0 0 9.53 9.357");
}

</style>
