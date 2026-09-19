<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#iDdnixi)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path fill="url(#iPvYsCI)" class="zannmacjr"/><path fill="url(#ijrew7g)" class="zannmacjr"/><path fill="url(#i33dVxW)" class="zannmacjr"/><path fill="url(#i8Ijlvb)" class="zannmacjr"/><path fill="url(#i9SARQb)" class="zannmacjr"/><path fill="url(#iD23Cgd)" class="zannmacjr"/><path fill="url(#iyzMEgd)" class="zannmacjr"/><path clip-rule="evenodd" class="e-6v6hbge"/><path fill="url(#iKU60Td)" clip-rule="evenodd" class="bk57nybfo"/><path fill="url(#iXpjkpd)" clip-rule="evenodd" class="bk57nybfo"/><path fill="url(#iOpwHpc)" clip-rule="evenodd" class="bk57nybfo"/><path fill="url(#iYmvuYS)" clip-rule="evenodd" class="bk57nybfo"/><path fill="url(#iHmncze)" clip-rule="evenodd" class="bk57nybfo"/><path fill="url(#it81N2e)" clip-rule="evenodd" class="bk57nybfo"/><path fill="url(#igukj6v)" clip-rule="evenodd" class="bk57nybfo"/><path fill="url(#i1t9Tde)" clip-rule="evenodd" class="k1kmaz97v"/><path fill="url(#ikIaZIe)" clip-rule="evenodd" class="x2b5oxgcm"/><path fill="url(#itusZ1c)" class="hjo4y55cd"/><path fill="url(#iNNi3Fe)" class="hjo4y55cd"/><path fill="url(#iapEPgc)" class="h9jqqganw"/><path class="gk2pz5bsp"/><path clip-rule="evenodd" class="vhtpo_10j"/></g><defs><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="iDdnixi" cx="0" cy="0" r="1" gradientTransform="rotate(76.632 -3.024 18.285)scale(28.2658)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="rbh43lblc"/><stop offset=".784" class="w9_b2xnds"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iPvYsCI" cx="0" cy="0" r="1" gradientTransform="rotate(-54.858 18.376 -1.718)scale(7.0017)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="f5322sbfu"/><stop offset="1" class="luu9z8b7s"/></radialGradient><radialGradient id="ijrew7g" cx="0" cy="0" r="1" gradientTransform="matrix(4.17314 1.29881 -.57676 1.85316 9.488 17.19)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b_kzqccii"/><stop offset="1" class="obqiathdk"/></radialGradient><radialGradient id="i33dVxW" cx="0" cy="0" r="1" gradientTransform="rotate(57.216 -3.355 26.463)scale(5.31724)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="b_kzqccii"/><stop offset=".807" class="obqiathdk"/></radialGradient><radialGradient id="i8Ijlvb" cx="0" cy="0" r="1" gradientTransform="rotate(48.991 1.107 31.002)scale(1.36135 .81622)" gradientUnits="userSpaceOnUse"><stop class="y4slsyb0d"/><stop offset="1" class="p7gdo4bqv"/></radialGradient><radialGradient id="i9SARQb" cx="0" cy="0" r="1" gradientTransform="rotate(44.132 .8 33.007)scale(2.28952 1.1424)" gradientUnits="userSpaceOnUse"><stop class="y4slsyb0d"/><stop offset="1" class="p7gdo4bqv"/></radialGradient><radialGradient id="iD23Cgd" cx="0" cy="0" r="1" gradientTransform="matrix(2.66234 1.66464 -.60787 .9722 21.517 7.778)" gradientUnits="userSpaceOnUse"><stop class="q5t8yyido"/><stop offset="1" class="qk_bhbcao"/></radialGradient><radialGradient id="iyzMEgd" cx="0" cy="0" r="1" gradientTransform="rotate(4.192 -92.114 277.02)scale(3.27224 1.68482)" gradientUnits="userSpaceOnUse"><stop class="q5t8yyido"/><stop offset="1" class="miffccc1q"/></radialGradient><radialGradient id="iKU60Td" cx="0" cy="0" r="1" gradientTransform="rotate(-114.874 16.248 2.157)scale(5.42052)" gradientUnits="userSpaceOnUse"><stop offset=".61" class="u-u_g1lzh"/><stop offset=".732" class="xipei47ye"/><stop offset=".795" class="xipei47ye"/><stop offset=".911" class="lfb6bfp0s"/></radialGradient><radialGradient id="iXpjkpd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47376 -6.05205 4.49872 -1.0955 16.585 24.388)" gradientUnits="userSpaceOnUse"><stop offset=".516" class="u-u_g1lzh"/><stop offset=".732" class="xipei47ye"/><stop offset=".791" class="xipei47ye"/><stop offset=".894" class="js23mbcbf"/></radialGradient><radialGradient id="iOpwHpc" cx="0" cy="0" r="1" gradientTransform="rotate(-25.534 48.925 -14.281)scale(5.93402 4.41098)" gradientUnits="userSpaceOnUse"><stop offset=".516" class="u-u_g1lzh"/><stop offset=".732" class="xipei47ye"/><stop offset=".791" class="xipei47ye"/><stop offset=".894" class="js23mbcbf"/></radialGradient><radialGradient id="iYmvuYS" cx="0" cy="0" r="1" gradientTransform="matrix(1.8277 -1.59924 .80682 .92208 13.27 24.082)" gradientUnits="userSpaceOnUse"><stop offset=".474" class="axrcxcbkf"/><stop offset=".957" class="s3a0bqjha"/></radialGradient><radialGradient id="iHmncze" cx="0" cy="0" r="1" gradientTransform="matrix(.76549 -2.57089 5.5795 1.6613 19.014 24.093)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="oy33qcb_x"/><stop offset=".756" class="ke44mkb7u"/></radialGradient><radialGradient id="it81N2e" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71931 -.29085 .14674 -1.3719 17.84 18.803)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="axrcxcbkf"/><stop offset=".634" class="s3a0bqjha"/></radialGradient><radialGradient id="igukj6v" cx="0" cy="0" r="1" gradientTransform="rotate(-108.898 13.997 4.19)scale(1.7061 4.24373)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="axrcxcbkf"/><stop offset=".634" class="s3a0bqjha"/></radialGradient><radialGradient id="itusZ1c" cx="0" cy="0" r="1" gradientTransform="matrix(3.14437 -2.62587 3.50326 4.19501 21.323 10)" gradientUnits="userSpaceOnUse"><stop offset=".61" class="u-u_g1lzh"/><stop offset=".732" class="xipei47ye"/><stop offset=".795" class="xipei47ye"/><stop offset=".851" class="zid5bib0z"/><stop offset=".911" class="lfb6bfp0s"/></radialGradient><radialGradient id="iNNi3Fe" cx="0" cy="0" r="1" gradientTransform="matrix(2.25003 -3.31268 2.99591 2.03487 21.653 9.036)" gradientUnits="userSpaceOnUse"><stop offset=".646" class="f9hmxbczz"/><stop offset="1" class="zd74ke3mf"/></radialGradient><radialGradient id="iapEPgc" cx="0" cy="0" r="1" gradientTransform="matrix(1.8361 3.03367 -3.86153 2.33715 9.32 9.852)" gradientUnits="userSpaceOnUse"><stop offset=".688" class="e9kszrbto"/><stop offset=".776" class="ph-k2-u8j"/><stop offset=".819" class="es85f4bow"/><stop offset=".898" class="jp9t1ybnb"/></radialGradient><linearGradient id="i1t9Tde" x1="11.37" x2="10.381" y1="12.797" y2="16.844" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="ikIaZIe" x1="21.188" x2="19.201" y1="10.676" y2="16.446" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woozy-face" /></template>
<style>
.axrcxcbkf {
  stop-color: var(--svg-color--392734, #392734);
}

.b_kzqccii {
  stop-color: var(--svg-color--d67b36, #D67B36);
}

.bk57nybfo {
  fill-rule: evenodd;
  d: path("M14.384 22.4c-.774.904-1.909 2.1-3.884 2.1c-1.968 0-3.608-1.194-4.207-1.793a1 1 0 1 1 1.414-1.414c.4.4 1.561 1.207 2.793 1.207c1.025 0 1.64-.554 2.366-1.4l.194-.23c.293-.35.637-.758 1-1.076c.48-.42 1.111-.794 1.94-.794c1.282 0 2.138.63 2.764 1.09l.137.101c.643.468 1.176.809 2.099.809c1.665 0 2.52-.832 2.668-1.055a1 1 0 0 1 1.664 1.11C24.814 21.832 23.335 23 21 23c-1.577 0-2.544-.659-3.276-1.191l-.033-.024C16.975 21.264 16.613 21 16 21c-.171 0-.352.063-.623.3c-.237.207-.453.463-.735.797l-.258.304");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.e-6v6hbge {
  fill: var(--svg-color--402a32, #402A32);
  fill-rule: evenodd;
  d: path("M14.384 22.4c-.774.904-1.909 2.1-3.884 2.1c-1.968 0-3.608-1.194-4.207-1.793a1 1 0 1 1 1.414-1.414c.4.4 1.561 1.207 2.793 1.207c1.025 0 1.64-.554 2.366-1.4l.194-.23c.293-.35.637-.758 1-1.076c.48-.42 1.111-.794 1.94-.794c1.282 0 2.138.63 2.764 1.09l.137.101c.643.468 1.176.809 2.099.809c1.665 0 2.52-.832 2.668-1.055a1 1 0 0 1 1.664 1.11C24.814 21.832 23.335 23 21 23c-1.577 0-2.544-.659-3.276-1.191l-.033-.024C16.975 21.264 16.613 21 16 21c-.171 0-.352.063-.623.3c-.237.207-.453.463-.735.797l-.258.304");
}

.e9kszrbto {
  stop-color: var(--svg-color--4a2f37, #4A2F37);
}

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
}

.es85f4bow {
  stop-color: var(--svg-color--5c4156, #5C4156);
}

.f5322sbfu {
  stop-color: var(--svg-color--c68f11, #C68F11);
}

.f9hmxbczz {
  stop-color: var(--svg-color--362530, #362530);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.gk2pz5bsp {
  fill: var(--svg-color--fff, #fff);
  d: path("M25.238 13.11c.2.236.269.553.241.862c-.246 2.735-2.613 4.501-4.979 4.028c-2.3-.46-3.753-2.612-3.582-4.9c.03-.394.222-.764.553-.978c2.115-1.37 6.412-.613 7.767.987M7 15c.167 1.167 1.172 3 4 3c4.5 0 4-6 4-6z");
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.h9jqqganw {
  d: path("M12.985 9.621a.5.5 0 1 0-.97-.242c-.36 1.442-1.164 2.149-2 2.482c-.865.344-1.805.301-2.394.154a.5.5 0 0 0-.242.97c.744.186 1.905.243 3.006-.195c1.13-.45 2.16-1.41 2.6-3.169");
}

.hjo4y55cd {
  d: path("M19.562 6.996c1.823-.228 2.918.448 3.57 1.156a4.3 4.3 0 0 1 .88 1.464l.007.02v.003a.5.5 0 0 0 .962-.276V9.36l-.002-.004l-.003-.012l-.013-.038l-.045-.13a5.3 5.3 0 0 0-1.05-1.703c-.848-.917-2.253-1.741-4.43-1.469a.5.5 0 0 0 .124.992");
}

.jp9t1ybnb {
  stop-color: var(--svg-color--4d3635, #4D3635);
}

.js23mbcbf {
  stop-color: var(--svg-color--533b4e, #533B4E);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k1kmaz97v {
  fill-rule: evenodd;
  d: path("M11 17a3 3 0 0 0 2.94-3.602l-5.55 2.081A3 3 0 0 0 11 17");
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.ke44mkb7u {
  stop-color: var(--svg-color--452f3f, #452F3F);
  stop-opacity: 0;
}

.kiu9e17zs {
  stop-color: var(--svg-color--3d2432, #3D2432);
}

.lfb6bfp0s {
  stop-color: var(--svg-color--442e3e, #442E3E);
}

.luu9z8b7s {
  stop-color: var(--svg-color--d59a13, #D59A13);
  stop-opacity: 0;
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.miffccc1q {
  stop-color: var(--svg-color--ffdc64, #FFDC64);
  stop-opacity: 0;
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.obqiathdk {
  stop-color: var(--svg-color--f79a38, #F79A38);
  stop-opacity: 0;
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.oy33qcb_x {
  stop-color: var(--svg-color--452f3f, #452F3F);
}

.p7gdo4bqv {
  stop-color: var(--svg-color--e39632, #E39632);
  stop-opacity: 0;
}

.ph-k2-u8j {
  stop-color: var(--svg-color--563e48, #563E48);
}

.q5t8yyido {
  stop-color: var(--svg-color--e2981b, #E2981B);
}

.qk_bhbcao {
  stop-color: var(--svg-color--eaa239, #EAA239);
  stop-opacity: 0;
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rbh43lblc {
  stop-color: var(--svg-color--d1671a, #D1671A);
  stop-opacity: 0;
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.s3a0bqjha {
  stop-color: var(--svg-color--392734, #392734);
  stop-opacity: 0;
}

.u-u_g1lzh {
  stop-color: var(--svg-color--2f1f2a, #2F1F2A);
}

.vhtpo_10j {
  fill: var(--svg-color--402a32, #402A32);
  fill-rule: evenodd;
  d: path("M21 15a2 2 0 0 0 1.491-3.333a8.8 8.8 0 0 0-2.736-.233A2 2 0 0 0 21 15m-10 1a2 2 0 0 0 1.656-3.121l-3.641 1.366A2 2 0 0 0 11 16");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.w9_b2xnds {
  stop-color: var(--svg-color--b2753d, #B2753D);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.x2b5oxgcm {
  fill-rule: evenodd;
  d: path("M21 17a3 3 0 0 0 2.635-4.435l-3.026-.84a3.9 3.9 0 0 0-1.405-.128A3 3 0 0 0 21 17");
}

.xipei47ye {
  stop-color: var(--svg-color--51394c, #51394C);
}

.y4slsyb0d {
  stop-color: var(--svg-color--e7982e, #E7982E);
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zd74ke3mf {
  stop-color: var(--svg-color--342330, #342330);
}

.zid5bib0z {
  stop-color: var(--svg-color--50394c, #50394C);
}

</style>
