<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#icq6bJi)" class="m40x8ab7l"/><path fill="url(#iFMhQPc)" class="m40x8ab7l"/><path fill="url(#iB8x0cd)" class="gyk71cc1x"/><path fill="url(#iGZGbQc)" class="gyk71cc1x"/><path fill="url(#imo5SIc)" class="ioriuyb4z"/><path fill="url(#i1X8f4d)" class="ioriuyb4z"/><path fill="url(#iBSj9Kc)" class="ioriuyb4z"/><path fill="url(#ifOcYHb)" class="ioriuyb4z"/><path fill="url(#ifdalMe)" class="ioriuyb4z"/><path fill="url(#iWZHb3d)" class="ioriuyb4z"/><path fill="url(#imx8wAd)" class="ioriuyb4z"/><path fill="url(#ipXPRGd)" class="ioriuyb4z"/><path fill="url(#iqiiEdc)" class="ioriuyb4z"/><path fill="url(#i16KP0b)" class="ioriuyb4z"/><circle fill="url(#iVYx6eb)" class="o2i3mb3st"/><circle fill="url(#ibvN6hd)" transform="rotate(90 22.763 13.284)" class="y22okx4wj"/><circle fill="url(#i6X6Qic)" class="cwozc4ben"/><circle fill="url(#ixA1gBl)" transform="rotate(90 22.763 17.753)" class="hx_9g8-cq"/><circle fill="url(#iGlmQbe)" class="ypyn5fb5p"/><circle fill="url(#iAVZqbj)" class="ypyn5fb5p"/><circle fill="url(#imMKvub)" class="v3x4gsbhv"/><circle fill="url(#iXot4Kn)" class="v3x4gsbhv"/><g filter="url(#iJAFtjd)"><path fill="url(#iPJfdIW)" class="ltsq2-i8h"/></g><defs><radialGradient id="i1X8f4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.12074 10.6947 0 15.93 26.462)" gradientUnits="userSpaceOnUse"><stop offset=".357" class="ypnainbyk"/><stop offset="1" class="ehrfzqbrk"/></radialGradient><radialGradient id="iBSj9Kc" cx="0" cy="0" r="1" gradientTransform="rotate(-107.504 25.288 2.812)scale(7.77665 8.72353)" gradientUnits="userSpaceOnUse"><stop class="f6rn21boo"/><stop offset="1" class="ho1cqfltz"/></radialGradient><radialGradient id="ifOcYHb" cx="0" cy="0" r="1" gradientTransform="rotate(90 -2.89 12.578)scale(2.46875)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="lx_nddbbr"/><stop offset="1" class="xqpbc1gew"/></radialGradient><radialGradient id="ifdalMe" cx="0" cy="0" r="1" gradientTransform="rotate(90 -.625 19.969)scale(2.46875)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="lx_nddbbr"/><stop offset="1" class="xqpbc1gew"/></radialGradient><radialGradient id="iWZHb3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.5 -1.5 0 20.484 15.5)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="lx_nddbbr"/><stop offset="1" class="xqpbc1gew"/></radialGradient><radialGradient id="imx8wAd" cx="0" cy="0" r="1" gradientTransform="rotate(90 2.496 20.262)scale(1.49219)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="lx_nddbbr"/><stop offset="1" class="xqpbc1gew"/></radialGradient><radialGradient id="ipXPRGd" cx="0" cy="0" r="1" gradientTransform="rotate(90 4.719 20.234)scale(1.46094)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="lx_nddbbr"/><stop offset="1" class="xqpbc1gew"/></radialGradient><radialGradient id="iqiiEdc" cx="0" cy="0" r="1" gradientTransform="rotate(90 4.734 18.023)scale(1.42969)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="lx_nddbbr"/><stop offset="1" class="xqpbc1gew"/></radialGradient><radialGradient id="i16KP0b" cx="0" cy="0" r="1" gradientTransform="rotate(90 -3.695 16.93)scale(2.71875)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="lx_nddbbr"/><stop offset="1" class="xqpbc1gew"/></radialGradient><radialGradient id="iVYx6eb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79688 0 0 -1.56812 21.68 15.312)" gradientUnits="userSpaceOnUse"><stop class="cp11-1gcm"/><stop offset="1" class="kv133hzhh"/></radialGradient><radialGradient id="ibvN6hd" cx="0" cy="0" r="1" gradientTransform="scale(1.84766 2.11719)rotate(90 3.24 9.08)" gradientUnits="userSpaceOnUse"><stop class="ctvb5ubpp"/><stop offset="1" class="cnh60o7ya"/></radialGradient><radialGradient id="i6X6Qic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79688 0 0 -1.56812 26.15 15.312)" gradientUnits="userSpaceOnUse"><stop class="hj15_5pvh"/><stop offset="1" class="l1yd_ssww"/></radialGradient><radialGradient id="ixA1gBl" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.11719 -1.84766 0 22.763 16.835)" gradientUnits="userSpaceOnUse"><stop class="ybu-2jbkn"/><stop offset="1" class="fo6ojsvqc"/></radialGradient><radialGradient id="iGlmQbe" cx="0" cy="0" r="1" gradientTransform="rotate(160.894 4.584 8.496)scale(3.92162 3.62455)" gradientUnits="userSpaceOnUse"><stop class="z7rc_ks6a"/><stop offset="1" class="bzaiekbbq"/></radialGradient><radialGradient id="iAVZqbj" cx="0" cy="0" r="1" gradientTransform="rotate(90 -3.69 13.417)scale(1.59741)" gradientUnits="userSpaceOnUse"><stop class="irex3bi0i"/><stop offset="1" class="i05k31b4v"/></radialGradient><radialGradient id="imMKvub" cx="0" cy="0" r="1" gradientTransform="matrix(-3.00258 1.41822 -1.31079 -2.77513 20.603 19.936)" gradientUnits="userSpaceOnUse"><stop class="z7rc_ks6a"/><stop offset="1" class="bzaiekbbq"/></radialGradient><radialGradient id="iXot4Kn" cx="0" cy="0" r="1" gradientTransform="rotate(90 -1.408 20.745)scale(1.59741)" gradientUnits="userSpaceOnUse"><stop class="irex3bi0i"/><stop offset="1" class="i05k31b4v"/></radialGradient><radialGradient id="iPJfdIW" cx="0" cy="0" r="1" gradientTransform="rotate(136.975 3.297 12.672)scale(2.56479 2.3607)" gradientUnits="userSpaceOnUse"><stop class="xzh9wxg7e"/><stop offset="1" class="e4syt0bwk"/></radialGradient><linearGradient id="icq6bJi" x1="6.696" x2="12.103" y1="11.53" y2="9.124" gradientUnits="userSpaceOnUse"><stop class="goh1b_b8z"/><stop offset=".355" class="warsmhr9e"/></linearGradient><linearGradient id="iFMhQPc" x1="13.306" x2="11.9" y1="9.046" y2="9.483" gradientUnits="userSpaceOnUse"><stop offset=".827" class="t3h6-qn1m"/><stop offset="1" class="jgwm_9xth"/></linearGradient><linearGradient id="iB8x0cd" x1="20.353" x2="24.946" y1="8.999" y2="10.718" gradientUnits="userSpaceOnUse"><stop class="fekwgyb8o"/><stop offset="1" class="me516cblh"/></linearGradient><linearGradient id="iGZGbQc" x1="18.962" x2="20.048" y1="9.515" y2="9.765" gradientUnits="userSpaceOnUse"><stop offset=".83" class="pszvkhvmb"/><stop offset="1" class="wn1ju2brb"/></linearGradient><linearGradient id="imo5SIc" x1="15.931" x2="15.931" y1="9.749" y2="25.374" gradientUnits="userSpaceOnUse"><stop class="ql16d8ohv"/><stop offset="1" class="nbc_egbhu"/></linearGradient><filter id="iJAFtjd" width="4.803" height="4.803" x="10.803" y="18.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.568627 0 0 0 0 0.945098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_606"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.360784 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3_606" result="effect2_innerShadow_3_606"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:video-game" /></template>
<style>
.bzaiekbbq {
  stop-color: var(--svg-color--6969bd, #6969BD);
}

.cnh60o7ya {
  stop-color: var(--svg-color--eeb84d, #EEB84D);
}

.cp11-1gcm {
  stop-color: var(--svg-color--5cc5ff, #5CC5FF);
}

.ctvb5ubpp {
  stop-color: var(--svg-color--ffde74, #FFDE74);
}

.cwozc4ben {
  cx: 24.95px;
  cy: 15.519px;
  r: 1.199px;
}

.e4syt0bwk {
  stop-color: var(--svg-color--8076e3, #8076E3);
}

.ehrfzqbrk {
  stop-color: var(--svg-color--5e2696, #5E2696);
  stop-opacity: 0;
}

.f6rn21boo {
  stop-color: var(--svg-color--6a4592, #6A4592);
}

.fekwgyb8o {
  stop-color: var(--svg-color--521852, #521852);
}

.fo6ojsvqc {
  stop-color: var(--svg-color--21e28c, #21E28C);
}

.ft5dv1b6b {
  fill: none;
}

.goh1b_b8z {
  stop-color: var(--svg-color--3c1b3c, #3C1B3C);
}

.gyk71cc1x {
  d: path("M23.68 9.108c1.563.735 2.522 2.23 2.75 2.954l-8.312-1.532l1.898-1.927a.44.44 0 0 1 .304-.137c.68-.012 2.414.148 3.36.642");
}

.hj15_5pvh {
  stop-color: var(--svg-color--ff5b74, #FF5B74);
}

.ho1cqfltz {
  stop-color: var(--svg-color--6a4592, #6A4592);
  stop-opacity: 0;
}

.hx_9g8-cq {
  cx: 22.763px;
  cy: 17.753px;
  r: 1.199px;
}

.i05k31b4v {
  stop-color: var(--svg-color--806fe7, #806FE7);
  stop-opacity: 0;
}

.ioriuyb4z {
  d: path("M9.466 9.749c-2.172 0-4.103 1.4-4.7 3.489a162 162 0 0 0-2.57 10.324c-.254 1.29-.39 3.796.422 5.046c1.313 1.813 2.636 1.7 4.078.546l4.034-3.231a2.5 2.5 0 0 1 1.563-.549h7.276a2.5 2.5 0 0 1 1.562.549l4.035 3.23c1.442 1.156 2.765 1.268 4.077-.545c.813-1.25.676-3.756.422-5.047c0 0-1.012-4.877-2.569-10.323c-.597-2.088-2.529-3.489-4.7-3.489z");
}

.irex3bi0i {
  stop-color: var(--svg-color--806fe7, #806FE7);
}

.jgwm_9xth {
  stop-color: var(--svg-color--613060, #613060);
  stop-opacity: 0;
}

.kv133hzhh {
  stop-color: var(--svg-color--259af4, #259AF4);
}

.l1yd_ssww {
  stop-color: var(--svg-color--f21f4d, #F21F4D);
}

.ltsq2-i8h {
  d: path("M13.204 18.296a.57.57 0 0 0-.57.57v.711a.5.5 0 0 1-.5.5h-.711a.57.57 0 0 0 0 1.14h.71a.5.5 0 0 1 .5.5v.712a.57.57 0 0 0 1.142 0v-.711a.5.5 0 0 1 .5-.5h.71a.57.57 0 0 0 0-1.14h-.71a.5.5 0 0 1-.5-.5v-.712a.57.57 0 0 0-.57-.57");
}

.lx_nddbbr {
  stop-color: var(--svg-color--4a3383, #4A3383);
}

.m40x8ab7l {
  d: path("M8.212 9.108c-1.562.735-2.52 2.23-2.75 2.954l8.313-1.532l-1.899-1.927a.44.44 0 0 0-.303-.137c-.68-.012-2.414.148-3.36.642");
}

.me516cblh {
  stop-color: var(--svg-color--603260, #603260);
}

.nbc_egbhu {
  stop-color: var(--svg-color--562f80, #562F80);
}

.o2i3mb3st {
  cx: 20.482px;
  cy: 15.519px;
  r: 1.199px;
}

.pszvkhvmb {
  stop-color: var(--svg-color--3d193d, #3D193D);
}

.ql16d8ohv {
  stop-color: var(--svg-color--6259a7, #6259A7);
}

.t3h6-qn1m {
  stop-color: var(--svg-color--613060, #613060);
}

.v3x4gsbhv {
  cx: 19.337px;
  cy: 20.53px;
  r: 1.969px;
}

.warsmhr9e {
  stop-color: var(--svg-color--501752, #501752);
}

.wn1ju2brb {
  stop-color: var(--svg-color--3d193d, #3D193D);
  stop-opacity: 0;
}

.xqpbc1gew {
  stop-color: var(--svg-color--4a3383, #4A3383);
  stop-opacity: 0;
}

.xzh9wxg7e {
  stop-color: var(--svg-color--8886e9, #8886E9);
}

.y22okx4wj {
  cx: 22.763px;
  cy: 13.284px;
  r: 1.199px;
}

.ybu-2jbkn {
  stop-color: var(--svg-color--57fba4, #57FBA4);
}

.ypnainbyk {
  stop-color: var(--svg-color--5e2696, #5E2696);
}

.ypyn5fb5p {
  cx: 9.728px;
  cy: 15.483px;
  r: 1.969px;
}

.z7rc_ks6a {
  stop-color: var(--svg-color--9395e9, #9395E9);
}

</style>
