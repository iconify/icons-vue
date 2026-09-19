<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iAGkUue)" class="m8rczwv4y"/><path fill="url(#i1o83Qd)" class="m8rczwv4y"/><path fill="url(#iwiafab)" class="m8rczwv4y"/><g filter="url(#iIICPZc)"><path fill="url(#ioqd5ld)" class="s47mtx_bc"/></g><path fill="url(#iWYX6hb)" class="u4jn1sbsi"/><path fill="url(#ilM1Gfd)" class="u4jn1sbsi"/><path fill="url(#iiD6Gzd)" class="u4jn1sbsi"/><g filter="url(#i42tCdb)"><path fill="url(#i8L4Wfc)" class="c4pg0jb2f"/><path fill="url(#iq2FXJc)" class="c4pg0jb2f"/></g><g filter="url(#iaTz1jd)"><path fill="url(#i86Qm3c)" class="n4l9q8w4u"/><path fill="url(#icXYcrd)" class="n4l9q8w4u"/></g><path fill="url(#iyTcHSc)" class="qmu-_7b9y"/><path fill="url(#iS6vRdb)" class="qmu-_7b9y"/><path fill="url(#iyD1r5d)" class="u8zoawb7c"/><path fill="url(#iTl1y7d)" class="u8zoawb7c"/><g filter="url(#iPyLxQe)"><path fill="url(#i30uROb)" class="zy82jdbcg"/></g><g filter="url(#i9HFLZN)"><path fill="url(#id6mIPb)" class="n76grbe5g"/><path fill="url(#imXOYOd)" class="n76grbe5g"/></g><g filter="url(#iPRscNq)"><path fill="url(#izDtIre)" class="wyesh9bdb"/></g><g filter="url(#izaDbkd)"><path fill="url(#io1roct)" class="wuoc-bc3b"/><path fill="url(#iqfIwIb)" class="wuoc-bc3b"/></g><defs><linearGradient id="iAGkUue" x1="3.05" x2="27.958" y1="10.5" y2="10.5" gradientUnits="userSpaceOnUse"><stop class="gho77rjzj"/><stop offset="1" class="h14gl52mt"/></linearGradient><linearGradient id="i1o83Qd" x1="3.05" x2="4.645" y1="13.176" y2="13.176" gradientUnits="userSpaceOnUse"><stop offset=".332" class="bjd_f0sza"/><stop offset="1" class="dw9pqgm5x"/></linearGradient><linearGradient id="ioqd5ld" x1="18.205" x2="13.137" y1="3.524" y2="8.169" gradientUnits="userSpaceOnUse"><stop class="wm56fwbiu"/><stop offset="1" class="h4it0zbee"/></linearGradient><linearGradient id="iWYX6hb" x1="3.044" x2="29.049" y1="22.999" y2="22.999" gradientUnits="userSpaceOnUse"><stop class="akx9u_b7o"/><stop offset="1" class="t098hro8x"/></linearGradient><linearGradient id="ilM1Gfd" x1="16.05" x2="16.05" y1="24.219" y2="23.313" gradientUnits="userSpaceOnUse"><stop class="swmcdi8em"/><stop offset="1" class="tkkxwkpxn"/></linearGradient><linearGradient id="i8L4Wfc" x1="16.099" x2="19.31" y1="6.645" y2="6.645" gradientUnits="userSpaceOnUse"><stop class="jieexcyxi"/><stop offset="1" class="fnyws-bpn"/></linearGradient><linearGradient id="i86Qm3c" x1="16.099" x2="19.48" y1="8.625" y2="8.625" gradientUnits="userSpaceOnUse"><stop class="jieexcyxi"/><stop offset="1" class="fnyws-bpn"/></linearGradient><linearGradient id="iyTcHSc" x1="3.05" x2="11.739" y1="5.006" y2="5.006" gradientUnits="userSpaceOnUse"><stop class="b79i9vkwe"/><stop offset="1" class="w4wrdybhl"/></linearGradient><linearGradient id="iS6vRdb" x1="7.05" x2="7.05" y1="3" y2="4.204" gradientUnits="userSpaceOnUse"><stop class="dpefvcbag"/><stop offset="1" class="v6ui99bzr"/></linearGradient><linearGradient id="iyD1r5d" x1="1.887" x2="27.402" y1="19.992" y2="19.992" gradientUnits="userSpaceOnUse"><stop class="hcyoxl0fb"/><stop offset="1" class="bd8dpvxwm"/></linearGradient><linearGradient id="iTl1y7d" x1="15.55" x2="15.55" y1="22.219" y2="21.531" gradientUnits="userSpaceOnUse"><stop class="hppgryboc"/><stop offset="1" class="dsm_2wb5y"/></linearGradient><linearGradient id="i30uROb" x1="12.564" x2="5.881" y1="26.52" y2="26.52" gradientUnits="userSpaceOnUse"><stop class="nextc782q"/><stop offset="1" class="y_8yqccti"/></linearGradient><linearGradient id="izDtIre" x1="27.521" x2="20.877" y1="26.5" y2="26.5" gradientUnits="userSpaceOnUse"><stop class="nextc782q"/><stop offset="1" class="y_8yqccti"/></linearGradient><radialGradient id="iwiafab" cx="0" cy="0" r="1" gradientTransform="matrix(-3.06251 9.3125 -7.29481 -2.39898 20.188 5.313)" gradientUnits="userSpaceOnUse"><stop class="l-tttsq4m"/><stop offset="1" class="bkbl5663u"/></radialGradient><radialGradient id="iiD6Gzd" cx="0" cy="0" r="1" gradientTransform="matrix(-17.9375 0 0 -.9375 26.769 22.781)" gradientUnits="userSpaceOnUse"><stop class="nncaiwbmq"/><stop offset="1" class="z1x034bwo"/></radialGradient><radialGradient id="iq2FXJc" cx="0" cy="0" r="1" gradientTransform="matrix(1.83333 0 0 .33969 17.005 6.595)" gradientUnits="userSpaceOnUse"><stop class="glqpi8ayd"/><stop offset="1" class="emldkqbaa"/></radialGradient><radialGradient id="icXYcrd" cx="0" cy="0" r="1" gradientTransform="matrix(1.93042 0 0 .33969 17.053 8.575)" gradientUnits="userSpaceOnUse"><stop class="glqpi8ayd"/><stop offset="1" class="emldkqbaa"/></radialGradient><radialGradient id="id6mIPb" cx="0" cy="0" r="1" gradientTransform="rotate(130.615 -1.501 15.105)scale(2.20823)" gradientUnits="userSpaceOnUse"><stop class="v5xad7b4h"/><stop offset=".8" class="suluofrzm"/></radialGradient><radialGradient id="imXOYOd" cx="0" cy="0" r="1" gradientTransform="rotate(-90 18.316 9.746)scale(1.14063)" gradientUnits="userSpaceOnUse"><stop class="ap7xrbcss"/><stop offset="1" class="ojkruib-w"/></radialGradient><radialGradient id="io1roct" cx="0" cy="0" r="1" gradientTransform="rotate(130.615 5.993 18.54)scale(2.20823)" gradientUnits="userSpaceOnUse"><stop class="v5xad7b4h"/><stop offset=".8" class="suluofrzm"/></radialGradient><radialGradient id="iqfIwIb" cx="0" cy="0" r="1" gradientTransform="rotate(-90 25.796 2.246)scale(1.14063)" gradientUnits="userSpaceOnUse"><stop class="ap7xrbcss"/><stop offset="1" class="ojkruib-w"/></radialGradient><filter id="iIICPZc" width="8.607" height="9.353" x="10.524" y="2.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11549" stdDeviation=".5"/></filter><filter id="i42tCdb" width="3.51" height="1.18" x="16.1" y="5.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.164706 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11549"/></filter><filter id="iaTz1jd" width="3.68" height="1.18" x="16.1" y="7.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.164706 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11549"/></filter><filter id="iPyLxQe" width="7.54" height="7.59" x="4.8" y="22.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.345098 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11549"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.411765 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11549" result="effect2_innerShadow_18_11549"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.345098 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_11549" result="effect3_innerShadow_18_11549"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.27451 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_11549" result="effect4_innerShadow_18_11549"/></filter><filter id="i9HFLZN" width="2.969" height="2.969" x="6.836" y="25.286" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.286275 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_11549"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_11549" result="shape"/></filter><filter id="iPRscNq" width="7.5" height="7.55" x="19.8" y="22.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.345098 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11549"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.411765 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11549" result="effect2_innerShadow_18_11549"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.345098 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_11549" result="effect3_innerShadow_18_11549"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.27451 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_11549" result="effect4_innerShadow_18_11549"/></filter><filter id="izaDbkd" width="2.969" height="2.969" x="21.816" y="25.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.286275 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_11549"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_11549" result="shape"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:roller-skate" /></template>
<style>
.akx9u_b7o {
  stop-color: var(--svg-color--726f73, #726F73);
}

.ap7xrbcss {
  stop-color: var(--svg-color--ad84b2, #AD84B2);
}

.b79i9vkwe {
  stop-color: var(--svg-color--3e3c3f, #3E3C3F);
}

.bd8dpvxwm {
  stop-color: var(--svg-color--7e678f, #7E678F);
}

.bjd_f0sza {
  stop-color: var(--svg-color--b13f74, #B13F74);
}

.bkbl5663u {
  stop-color: var(--svg-color--ff9a93, #FF9A93);
  stop-opacity: 0;
}

.c4pg0jb2f {
  d: path("M18.82 7.14h-2.23a.49.49 0 0 1 0-.98h2.23a.49.49 0 0 1 0 .98");
}

.dpefvcbag {
  stop-color: var(--svg-color--6e6775, #6E6775);
}

.dsm_2wb5y {
  stop-color: var(--svg-color--110f12, #110F12);
  stop-opacity: 0;
}

.dw9pqgm5x {
  stop-color: var(--svg-color--b13f74, #B13F74);
  stop-opacity: 0;
}

.emldkqbaa {
  stop-color: var(--svg-color--645e6b, #645E6B);
  stop-opacity: 0;
}

.fnyws-bpn {
  stop-color: var(--svg-color--816d8c, #816D8C);
}

.ft5dv1b6b {
  fill: none;
}

.gho77rjzj {
  stop-color: var(--svg-color--db3685, #DB3685);
}

.glqpi8ayd {
  stop-color: var(--svg-color--645e6b, #645E6B);
}

.h14gl52mt {
  stop-color: var(--svg-color--ffa566, #FFA566);
}

.h4it0zbee {
  stop-color: var(--svg-color--ff9da0, #FF9DA0);
  stop-opacity: 0;
}

.hcyoxl0fb {
  stop-color: var(--svg-color--322e35, #322E35);
}

.hppgryboc {
  stop-color: var(--svg-color--110f12, #110F12);
}

.jieexcyxi {
  stop-color: var(--svg-color--584b58, #584B58);
}

.l-tttsq4m {
  stop-color: var(--svg-color--ff9a93, #FF9A93);
}

.m8rczwv4y {
  d: path("M11.05 3v2.5c0 .842-.979 1.5-2 1.5h-6v11h25c0-4.291-5.757-5.224-6.948-5.896c-.38-.21-2.023-.666-2.283-2.14c-.154-1.286-.53-4.758-.53-4.758c-.261-1.284-1.312-2.196-2.524-2.196z");
}

.n4l9q8w4u {
  d: path("M18.96 9.12h-2.34c-.29 0-.52-.22-.52-.49s.23-.49.52-.49h2.34c.29 0 .52.22.52.49s-.24.49-.52.49");
}

.n76grbe5g {
  d: path("M8.57 27.754a1.234 1.234 0 1 0 0-2.468a1.234 1.234 0 0 0 0 2.468");
}

.nextc782q {
  stop-color: var(--svg-color--ff4b9e, #FF4B9E);
}

.nncaiwbmq {
  stop-color: var(--svg-color--ece3dc, #ECE3DC);
}

.ojkruib-w {
  stop-color: var(--svg-color--ad84b2, #AD84B2);
  stop-opacity: 0;
}

.qmu-_7b9y {
  d: path("M5.176 3.01c-1.001 0-2.126.656-2.126 2.002V7h6.166c1.011 0 1.834-.655 1.834-1.465V3z");
}

.s47mtx_bc {
  d: path("M15.648 3.792h-3.375a.749.749 0 1 0 0 1.498h2.954a1 1 0 0 1 .945.674l1.764 5.114c.039.111.205.076.195-.042l-.491-5.424a2 2 0 0 0-1.992-1.82");
}

.suluofrzm {
  stop-color: var(--svg-color--a7878d, #A7878D);
}

.swmcdi8em {
  stop-color: var(--svg-color--8c6896, #8C6896);
}

.t098hro8x {
  stop-color: var(--svg-color--d5c5c8, #D5C5C8);
}

.tkkxwkpxn {
  stop-color: var(--svg-color--8c6896, #8C6896);
  stop-opacity: 0;
}

.u4jn1sbsi {
  d: path("M28.09 24H4.01c-.53 0-.96-.449-.96-1s.43-1 .96-1h24.08c.53 0 .96.449.96 1s-.43 1-.96 1");
}

.u8zoawb7c {
  d: path("M26.298 22c.73 0 1.362-.486 1.622-1.134c.08-.203.13-.425.13-.658V18h-25v2.208c0 .233.05.455.13.658c.26.678.911 1.134 1.672 1.134");
}

.v5xad7b4h {
  stop-color: var(--svg-color--fff8f5, #FFF8F5);
}

.v6ui99bzr {
  stop-color: var(--svg-color--6e6775, #6E6775);
  stop-opacity: 0;
}

.w4wrdybhl {
  stop-color: var(--svg-color--765f88, #765F88);
}

.wm56fwbiu {
  stop-color: var(--svg-color--ff9da0, #FF9DA0);
}

.wuoc-bc3b {
  d: path("M23.55 27.734a1.234 1.234 0 1 0 0-2.469a1.234 1.234 0 0 0 0 2.47");
}

.wyesh9bdb {
  d: path("M23.55 30a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.y_8yqccti {
  stop-color: var(--svg-color--ff805f, #FF805F);
}

.z1x034bwo {
  stop-color: var(--svg-color--ece3dc, #ECE3DC);
  stop-opacity: 0;
}

.zy82jdbcg {
  d: path("M8.57 30.04a3.52 3.52 0 1 0 0-7.04a3.52 3.52 0 0 0 0 7.04");
}

</style>
