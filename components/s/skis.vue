<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iaQI5gc)" class="kms2tg-wy"/><path fill="url(#igDq9EV)" class="kms2tg-wy"/><path fill="url(#iNnZsFY)" class="kms2tg-wy"/><path fill="url(#iLVUqrb)" class="kms2tg-wy"/><path fill="url(#iM1t5EL)" class="kms2tg-wy"/><g filter="url(#ixP2Htb)"><path fill="url(#ikgIUKu)" class="s7qwf4yty"/></g><g filter="url(#iHEaooc)"><path class="xmczr487b"/><path fill="url(#iEdKxdd)" class="sokf2w_dz"/><path fill="url(#ifTsfLe)" class="sokf2w_dz"/><path fill="url(#ijzKElJ)" class="sokf2w_dz"/></g><g filter="url(#idtrcPS)"><path class="i0-uqwbzm"/><path fill="url(#icXbGEe)" class="i7guexb8w"/><path fill="url(#imbwvsC)" class="i7guexb8w"/></g><g filter="url(#iuWCjue)"><path class="g8v44dj5j"/></g><g filter="url(#ijuoWjc)"><path class="msv_5ko0a"/></g><path fill="url(#iHiMKPd)" class="hbesvacyi"/><path fill="url(#iE3lU7b)" class="hbesvacyi"/><path fill="url(#iB3FQde)" class="hbesvacyi"/><path fill="url(#i2iAnQE)" class="hbesvacyi"/><g filter="url(#iKNj2lr)"><path fill="url(#iF35BKs)" class="ee-y_kbgi"/></g><path fill="url(#idcVV3d)" class="ee-y_kbgi"/><path fill="url(#iWCcZQh)" class="ee-y_kbgi"/><path fill="url(#izgfVwc)" class="ee-y_kbgi"/><g filter="url(#iFuRnyL)"><path class="rjzro0b7m"/><path fill="url(#i8ydZHb)" class="s81dkcbpm"/><path fill="url(#iKEzf3F)" class="s81dkcbpm"/></g><g filter="url(#i3TQvFc)"><path stroke="url(#im5T5ze)" class="uj9pahbrj"/></g><g filter="url(#ipHnfWW)"><path stroke="url(#iJnJCBb)" class="vfpah7ckx"/></g><defs><linearGradient id="igDq9EV" x1="22.391" x2="18.838" y1="13.469" y2="15.729" gradientUnits="userSpaceOnUse"><stop class="x2ha28bti"/><stop offset="1" class="ggv7oj5zd"/></linearGradient><linearGradient id="iNnZsFY" x1="22.479" x2="21.767" y1="13.375" y2="13.883" gradientUnits="userSpaceOnUse"><stop class="tmrj68bzt"/><stop offset="1" class="iii6mlb0d"/></linearGradient><linearGradient id="ikgIUKu" x1="18.908" x2="11.214" y1="7.759" y2="12.156" gradientUnits="userSpaceOnUse"><stop class="o40xjeb0l"/><stop offset="1" class="j_45hfsma"/></linearGradient><linearGradient id="iEdKxdd" x1="23.317" x2="22.006" y1="15.77" y2="16.502" gradientUnits="userSpaceOnUse"><stop class="g8o2bubej"/><stop offset="1" class="u2tozbg2g"/></linearGradient><linearGradient id="ifTsfLe" x1="21.759" x2="21.345" y1="18.467" y2="17.842" gradientUnits="userSpaceOnUse"><stop class="mevixrbzk"/><stop offset="1" class="bttuor0le"/></linearGradient><linearGradient id="icXbGEe" x1="12.643" x2="11.691" y1="22.267" y2="22.854" gradientUnits="userSpaceOnUse"><stop class="g8o2bubej"/><stop offset="1" class="u2tozbg2g"/></linearGradient><linearGradient id="imbwvsC" x1="11.452" x2="11.178" y1="24.136" y2="23.678" gradientUnits="userSpaceOnUse"><stop class="mevixrbzk"/><stop offset="1" class="bttuor0le"/></linearGradient><linearGradient id="iE3lU7b" x1="12.251" x2="12.01" y1="11.699" y2="11.19" gradientUnits="userSpaceOnUse"><stop class="yb1l_fbjz"/><stop offset="1" class="nujwiac0x"/></linearGradient><linearGradient id="iB3FQde" x1="10.273" x2="11.1" y1="11.646" y2="11.146" gradientUnits="userSpaceOnUse"><stop class="id-dthbji"/><stop offset="1" class="c96nrzbrn"/></linearGradient><linearGradient id="i2iAnQE" x1="10.754" x2="11.078" y1="9.587" y2="10.163" gradientUnits="userSpaceOnUse"><stop class="r5u1dp_zf"/><stop offset="1" class="csm4w-b_s"/></linearGradient><linearGradient id="iF35BKs" x1="26.821" x2="4.557" y1="15.405" y2="30.015" gradientUnits="userSpaceOnUse"><stop class="h6omtxbyn"/><stop offset="1" class="d51v4_b8m"/></linearGradient><linearGradient id="i8ydZHb" x1="16.989" x2="15.963" y1="3.856" y2="4.369" gradientUnits="userSpaceOnUse"><stop class="kxm9u3bhy"/><stop offset="1" class="g9re3mq8e"/></linearGradient><linearGradient id="im5T5ze" x1="3.512" x2="10.024" y1="26.221" y2="28.118" gradientUnits="userSpaceOnUse"><stop class="pr26t6e5a"/><stop offset="1" class="y25c7tqul"/></linearGradient><linearGradient id="iJnJCBb" x1="27.922" x2="14.212" y1="15.827" y2="28.284" gradientUnits="userSpaceOnUse"><stop class="ga_iu8bvr"/><stop offset="1" class="hxrb5hbku"/></linearGradient><radialGradient id="iaQI5gc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.943 16.982 2.028)scale(6.07828 12.3674)" gradientUnits="userSpaceOnUse"><stop offset=".387" class="jowm3q-sz"/><stop offset="1" class="zg83qabgu"/></radialGradient><radialGradient id="iLVUqrb" cx="0" cy="0" r="1" gradientTransform="rotate(172.208 9.216 10.658)scale(2.99642 2.89636)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="zn59x8b0q"/><stop offset="1" class="xd4r0oyml"/></radialGradient><radialGradient id="iM1t5EL" cx="0" cy="0" r="1" gradientTransform="rotate(28.551 -20.967 27.684)scale(1.39445 3.53678)" gradientUnits="userSpaceOnUse"><stop class="cme-90b1c"/><stop offset="1" class="epi8arb_h"/></radialGradient><radialGradient id="ijzKElJ" cx="0" cy="0" r="1" gradientTransform="matrix(1.4288 -.87926 1.3019 2.1156 18.432 18.97)" gradientUnits="userSpaceOnUse"><stop class="jd9mv0b_x"/><stop offset="1" class="phz3-66_h"/></radialGradient><radialGradient id="iHiMKPd" cx="0" cy="0" r="1" gradientTransform="rotate(-118.61 9.588 2.362)scale(1.1285 3.52638)" gradientUnits="userSpaceOnUse"><stop class="j9nqqsb2b"/><stop offset="1" class="ka96z8brc"/></radialGradient><radialGradient id="idcVV3d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51308 .97269 -2.12833 -3.31076 29.559 15.009)" gradientUnits="userSpaceOnUse"><stop class="mtwgb320y"/><stop offset="1" class="rl6gqsvqh"/></radialGradient><radialGradient id="iWCcZQh" cx="0" cy="0" r="1" gradientTransform="matrix(-.17251 4.0539 -7.0783 -.30121 4.72 23.418)" gradientUnits="userSpaceOnUse"><stop class="b76etnb9z"/><stop offset="1" class="xmcb52yao"/></radialGradient><radialGradient id="izgfVwc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.31266 14.49055 -41.0435 -12.21532 10.844 16.086)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="hhvsm7glz"/><stop offset="1" class="q7pgus4ql"/></radialGradient><radialGradient id="iKEzf3F" cx="0" cy="0" r="1" gradientTransform="rotate(90.877 3.766 8.013)scale(1.52266 1.02743)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="db96nbc-o"/><stop offset="1" class="mi7po2dtg"/></radialGradient><filter id="ixP2Htb" width="12.733" height="11.774" x="9.027" y="3.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.611765 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2998"/></filter><filter id="iHEaooc" width="6.539" height="5.57" x="17.685" y="14.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.380392 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2998"/></filter><filter id="idtrcPS" width="5.068" height="3.889" x="8.339" y="21.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.407843 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2998"/></filter><filter id="iuWCjue" width="4.152" height="3.552" x="8.839" y="15.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2998"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.384314 0 0 0 0 0.819608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2998" result="effect2_innerShadow_18_2998"/></filter><filter id="ijuoWjc" width="3.969" height="3.389" x="9.546" y="8.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.713726 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2998"/></filter><filter id="iKNj2lr" width="28.003" height="16.375" x="1.947" y="13.89" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.223529 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2998"/></filter><filter id="iFuRnyL" width="8.235" height="6.184" x="8.662" y="2.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.376471 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2998"/></filter><filter id="i3TQvFc" width="9.505" height="4.662" x="2.935" y="24.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2998" stdDeviation=".325"/></filter><filter id="ipHnfWW" width="15.444" height="10.434" x="13.817" y="14.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2998" stdDeviation=".325"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:skis" /></template>
<style>
.b76etnb9z {
  stop-color: var(--svg-color--fe6a3a, #FE6A3A);
}

.bttuor0le {
  stop-color: var(--svg-color--3f77f2, #3F77F2);
  stop-opacity: 0;
}

.c96nrzbrn {
  stop-color: var(--svg-color--395fd4, #395FD4);
  stop-opacity: 0;
}

.cme-90b1c {
  stop-color: var(--svg-color--6aaed9, #6AAED9);
}

.csm4w-b_s {
  stop-color: var(--svg-color--4880c9, #4880C9);
  stop-opacity: 0;
}

.d51v4_b8m {
  stop-color: var(--svg-color--e8323a, #E8323A);
}

.db96nbc-o {
  stop-color: var(--svg-color--61aefb, #61AEFB);
}

.ee-y_kbgi {
  d: path("m9.007 29.393l20.6-12.61c.34-.21.44-.64.24-.98l-.96-1.57a.715.715 0 0 0-.98-.24l-20.6 12.61a.964.964 0 0 1-1.33-.32l-1-1.64a1.64 1.64 0 0 0-2.25-.54c-.77.47-1.01 1.48-.54 2.25l1 1.64a4.235 4.235 0 0 0 5.82 1.4");
}

.epi8arb_h {
  stop-color: var(--svg-color--6aaed9, #6AAED9);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g8o2bubej {
  stop-color: var(--svg-color--3d9ffa, #3D9FFA);
}

.g8v44dj5j {
  fill: var(--svg-color--367edd, #367EDD);
  d: path("m9.077 17.083l.76-1.4a.27.27 0 0 1 .38-.11l2.01 1.09c.52.28.72.94.43 1.46c-.28.52-.94.72-1.46.43l-2.01-1.09a.27.27 0 0 1-.11-.38");
}

.g9re3mq8e {
  stop-color: var(--svg-color--61affb, #61AFFB);
  stop-opacity: 0;
}

.ga_iu8bvr {
  stop-color: var(--svg-color--ff8441, #FF8441);
}

.ggv7oj5zd {
  stop-color: var(--svg-color--72cfff, #72CFFF);
  stop-opacity: 0;
}

.h6omtxbyn {
  stop-color: var(--svg-color--ff843a, #FF843A);
}

.hbesvacyi {
  d: path("m10.667 12.033l-.83-1.36a.29.29 0 0 1 .09-.39l1.95-1.2c.51-.31 1.17-.15 1.48.36s.15 1.17-.36 1.48l-1.95 1.2c-.13.08-.3.04-.38-.09");
}

.hhvsm7glz {
  stop-color: var(--svg-color--fe334c, #FE334C);
  stop-opacity: 0;
}

.hxrb5hbku {
  stop-color: var(--svg-color--ff8441, #FF8441);
  stop-opacity: 0;
}

.i0-uqwbzm {
  fill: var(--svg-color--468ff6, #468FF6);
  d: path("m10.226 24.885l.091-.072l2.79-1.71l-1.04-1.71a.5.5 0 0 0-.68-.16L8.34 23.102l.508.832l.38.619l.002.006l.008.014c.21.338.628.467.989.312");
}

.i7guexb8w {
  d: path("m10.226 24.885l.091-.072l2.79-1.71l-1.04-1.71a.5.5 0 0 0-.68-.16L8.34 23.102l.508.832l.38.619l.002.006l.008.014c.21.338.628.467.989.312");
}

.id-dthbji {
  stop-color: var(--svg-color--395fd4, #395FD4);
}

.iii6mlb0d {
  stop-color: var(--svg-color--6bc0ed, #6BC0ED);
  stop-opacity: 0;
}

.j_45hfsma {
  stop-color: var(--svg-color--8ad1fe, #8AD1FE);
}

.j9nqqsb2b {
  stop-color: var(--svg-color--3e81ed, #3E81ED);
}

.jd9mv0b_x {
  stop-color: var(--svg-color--3470e1, #3470E1);
}

.jowm3q-sz {
  stop-color: var(--svg-color--3fa4fe, #3FA4FE);
}

.ka96z8brc {
  stop-color: var(--svg-color--3e81ed, #3E81ED);
  stop-opacity: 0;
}

.kms2tg-wy {
  d: path("m21.46 11.805l-.291.045l-4.082 2.33c-1.87 1.15-4.37-1.243-5.82-1.828l.095.169a1 1 0 0 1 .006.967l-2.45 4.505l-.162.289c-.796 1.415-1.598 2.843-.709 4.34l.292.48h4.768l5.69-3.46l4.112-5.468z");
}

.kxm9u3bhy {
  stop-color: var(--svg-color--61affb, #61AFFB);
}

.mevixrbzk {
  stop-color: var(--svg-color--3f77f2, #3F77F2);
}

.mi7po2dtg {
  stop-color: var(--svg-color--61aefb, #61AEFB);
  stop-opacity: 0;
}

.msv_5ko0a {
  fill: var(--svg-color--3983e0, #3983E0);
  d: path("m10.667 12.033l-.83-1.36a.29.29 0 0 1 .09-.39l1.95-1.2c.51-.31 1.17-.15 1.48.36s.15 1.17-.36 1.48l-1.95 1.2c-.13.08-.3.04-.38-.09");
}

.mtwgb320y {
  stop-color: var(--svg-color--ffad5c, #FFAD5C);
}

.nujwiac0x {
  stop-color: var(--svg-color--3a7bf1, #3A7BF1);
  stop-opacity: 0;
}

.o40xjeb0l {
  stop-color: var(--svg-color--b6ffff, #B6FFFF);
}

.phz3-66_h {
  stop-color: var(--svg-color--3470e1, #3470E1);
  stop-opacity: 0;
}

.pr26t6e5a {
  stop-color: var(--svg-color--ff6d50, #FF6D50);
}

.q7pgus4ql {
  stop-color: var(--svg-color--fe334c, #FE334C);
}

.r5u1dp_zf {
  stop-color: var(--svg-color--4880c9, #4880C9);
}

.rjzro0b7m {
  fill: var(--svg-color--3e8ae3, #3E8AE3);
  d: path("m12.057 5.213l3.5-2.14c.22-.14.51-.07.65.14l.49.82l-.005.003v.11L9.146 8.784l-.119-.044c-.72-1.17-.34-2.707.83-3.427l1.14-.7c.19-.11.44-.05.56.14l.25.4c.05.09.16.11.25.06");
}

.rl6gqsvqh {
  stop-color: var(--svg-color--ffad5c, #FFAD5C);
  stop-opacity: 0;
}

.s7qwf4yty {
  d: path("m21.46 11.805l-1.903-3.112l-3.163-5.176l-7.367 5.226l2.4 3.91l.21.34l-.005.01l.055.09a3.98 3.98 0 0 0 5.47 1.31z");
}

.s81dkcbpm {
  d: path("m12.057 5.213l3.5-2.14c.22-.14.51-.07.65.14l.49.82l-.005.003v.11L9.146 8.784l-.119-.044c-.72-1.17-.34-2.707.83-3.427l1.14-.7c.19-.11.44-.05.56.14l.25.4c.05.09.16.11.25.06");
}

.sokf2w_dz {
  d: path("m22.91 14.173l-4.993 3.09c-.23.14-.3.45-.16.68l1.04 1.7l4.75-2.91c.37-.23.49-.71.26-1.09z");
}

.tmrj68bzt {
  stop-color: var(--svg-color--6bc0ed, #6BC0ED);
}

.u2tozbg2g {
  stop-color: var(--svg-color--3d9ffa, #3D9FFA);
  stop-opacity: 0;
}

.uj9pahbrj {
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("m3.857 25.057l1.269 1.95a2 2 0 0 0 2.719.615l3.775-2.307");
}

.vfpah7ckx {
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("m14.639 23.806l13.8-8.582");
}

.x2ha28bti {
  stop-color: var(--svg-color--72cfff, #72CFFF);
}

.xd4r0oyml {
  stop-color: var(--svg-color--3b69ca, #3B69CA);
  stop-opacity: 0;
}

.xmcb52yao {
  stop-color: var(--svg-color--fe6a3a, #FE6A3A);
  stop-opacity: 0;
}

.xmczr487b {
  fill: var(--svg-color--468ff6, #468FF6);
  d: path("m22.91 14.173l-4.993 3.09c-.23.14-.3.45-.16.68l1.04 1.7l4.75-2.91c.37-.23.49-.71.26-1.09z");
}

.y25c7tqul {
  stop-color: var(--svg-color--ff6d50, #FF6D50);
  stop-opacity: 0;
}

.yb1l_fbjz {
  stop-color: var(--svg-color--3a7bf1, #3A7BF1);
}

.zg83qabgu {
  stop-color: var(--svg-color--57c1ff, #57C1FF);
}

.zn59x8b0q {
  stop-color: var(--svg-color--3b69ca, #3B69CA);
}

</style>
