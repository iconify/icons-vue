<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixgdP9K)"><path fill="url(#ivvyVuF)" class="ch6ftyb8j"/></g><path fill="url(#iqHMocc)" class="j_fk-qkmu"/><path fill="url(#id4vK6c)" class="j_fk-qkmu"/><path fill="url(#i1Cungc)" class="j_fk-qkmu"/><path fill="url(#if298Yb)" class="w9295jtdi"/><path fill="url(#i4nisWc)" class="w9295jtdi"/><path fill="url(#ieWG06s)" class="w9295jtdi"/><path fill="url(#iAj2mRd)" class="xm1ad5bjr"/><path fill="url(#i5jtTnF)" class="xm1ad5bjr"/><path fill="url(#ifkQpMD)" class="xm1ad5bjr"/><path fill="url(#izGxaWd)" class="m--kmzbhi"/><path fill="url(#izBfvqe)" class="m--kmzbhi"/><path fill="url(#irPtckb)" class="m--kmzbhi"/><path fill="url(#iCAiZhe)" class="xt9395bxf"/><path fill="url(#iaMK47b)" class="xt9395bxf"/><path fill="url(#i1vXVza)" class="xt9395bxf"/><g filter="url(#iVL8dKd)"><path stroke="url(#i8pj15c)" class="f9nbtoboh"/></g><defs><linearGradient id="ivvyVuF" x1="3.032" x2="21.604" y1="25.794" y2="8.029" gradientUnits="userSpaceOnUse"><stop class="qqix0q3zw"/><stop offset="1" class="veenggb3h"/></linearGradient><linearGradient id="iqHMocc" x1="8.921" x2="27.36" y1="29.026" y2="7.038" gradientUnits="userSpaceOnUse"><stop class="f-nfj3b8m"/><stop offset="1" class="v8_-26bgx"/></linearGradient><linearGradient id="id4vK6c" x1="30.047" x2="29.066" y1="6.81" y2="6.81" gradientUnits="userSpaceOnUse"><stop class="qlo3vv0nr"/><stop offset="1" class="mlp_qzbem"/></linearGradient><linearGradient id="i1Cungc" x1="6.399" x2="6.399" y1="29.967" y2="29.436" gradientUnits="userSpaceOnUse"><stop offset=".326" class="z4btr4bzo"/><stop offset="1" class="oolkibb9v"/></linearGradient><linearGradient id="if298Yb" x1="11.446" x2="27.673" y1="29.139" y2="9.79" gradientUnits="userSpaceOnUse"><stop class="zy6mr92ve"/><stop offset="1" class="tdnyvfbtw"/></linearGradient><linearGradient id="i4nisWc" x1="30.038" x2="29.167" y1="9.589" y2="9.589" gradientUnits="userSpaceOnUse"><stop class="aqh-m2srp"/><stop offset="1" class="ltoxbabky"/></linearGradient><linearGradient id="ieWG06s" x1="9.227" x2="9.227" y1="29.967" y2="29.5" gradientUnits="userSpaceOnUse"><stop offset=".326" class="w2q8jobqq"/><stop offset="1" class="d1burtbgm"/></linearGradient><linearGradient id="iAj2mRd" x1="13.972" x2="27.986" y1="29.252" y2="12.541" gradientUnits="userSpaceOnUse"><stop class="djlayac2a"/><stop offset="1" class="q6y4jw46v"/></linearGradient><linearGradient id="i5jtTnF" x1="30.028" x2="29.133" y1="12.368" y2="12.368" gradientUnits="userSpaceOnUse"><stop class="vfiar2bra"/><stop offset="1" class="th1b9wytg"/></linearGradient><linearGradient id="ifkQpMD" x1="12.055" x2="12.055" y1="29.967" y2="29.564" gradientUnits="userSpaceOnUse"><stop offset=".326" class="j6nau6c8g"/><stop offset="1" class="lwmhkdbto"/></linearGradient><linearGradient id="izGxaWd" x1="16.497" x2="28.299" y1="29.365" y2="15.292" gradientUnits="userSpaceOnUse"><stop class="tde7r7b3t"/><stop offset="1" class="u3aztubom"/></linearGradient><linearGradient id="izBfvqe" x1="30.018" x2="29.265" y1="15.146" y2="15.146" gradientUnits="userSpaceOnUse"><stop class="li197rzkx"/><stop offset="1" class="vtpyaebyy"/></linearGradient><linearGradient id="irPtckb" x1="14.883" x2="14.883" y1="29.967" y2="29.627" gradientUnits="userSpaceOnUse"><stop offset=".326" class="a6sp08bnm"/><stop offset="1" class="rphqyf-xo"/></linearGradient><linearGradient id="iCAiZhe" x1="19.023" x2="28.611" y1="29.478" y2="18.044" gradientUnits="userSpaceOnUse"><stop class="pre4sg_6z"/><stop offset="1" class="ma48aem-o"/></linearGradient><linearGradient id="iaMK47b" x1="30.009" x2="29.396" y1="17.925" y2="17.925" gradientUnits="userSpaceOnUse"><stop class="lc952ppov"/><stop offset="1" class="h8cp8qb3m"/></linearGradient><linearGradient id="i1vXVza" x1="17.711" x2="17.711" y1="29.967" y2="29.691" gradientUnits="userSpaceOnUse"><stop offset=".326" class="qwgybgbsx"/><stop offset="1" class="zhmvymbwp"/></linearGradient><linearGradient id="i8pj15c" x1="19.828" x2="22.096" y1="28.583" y2="23.349" gradientUnits="userSpaceOnUse"><stop class="kv0dqfssy"/><stop offset="1" class="o99gzfqhk"/></linearGradient><filter id="ixgdP9K" width="28.483" height="28.433" x="1.733" y="1.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.286275 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15376"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.207843 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_15376" result="effect2_innerShadow_18_15376"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.368627 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_15376" result="effect3_innerShadow_18_15376"/></filter><filter id="iVL8dKd" width="3.621" height="6.718" x="18.944" y="22.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15376" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rainbow" /></template>
<style>
.a6sp08bnm {
  stop-color: var(--svg-color--6160ff, #6160FF);
}

.aqh-m2srp {
  stop-color: var(--svg-color--ffff9f, #FFFF9F);
}

.ch6ftyb8j {
  d: path("M29.967 17.967c0 1.104-.905 1.979-1.987 2.197a10.01 10.01 0 0 0-7.816 7.816c-.218 1.082-1.093 1.987-2.197 1.987h-14c-1.105 0-2.008-.897-1.929-1.999a28.02 28.02 0 0 1 8.129-17.801a28.02 28.02 0 0 1 17.801-8.129c1.102-.079 1.999.824 1.999 1.929z");
}

.d1burtbgm {
  stop-color: var(--svg-color--ff9783, #FF9783);
  stop-opacity: 0;
}

.djlayac2a {
  stop-color: var(--svg-color--48cf92, #48CF92);
}

.f-nfj3b8m {
  stop-color: var(--svg-color--ff8e54, #FF8E54);
}

.f9nbtoboh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M21.965 23.196c-.61.64-2.142 2.761-2.42 5.518");
}

.ft5dv1b6b {
  fill: none;
}

.h8cp8qb3m {
  stop-color: var(--svg-color--b28afa, #B28AFA);
  stop-opacity: 0;
}

.j_fk-qkmu {
  d: path("M29.967 17.967c0 1.104-.905 1.979-1.988 2.197a10.01 10.01 0 0 0-7.815 7.815c-.218 1.083-1.093 1.988-2.197 1.988h-13c0-6.63 2.64-12.99 7.32-17.68a25 25 0 0 1 17.68-7.32z");
}

.j6nau6c8g {
  stop-color: var(--svg-color--5e97b1, #5E97B1);
}

.kv0dqfssy {
  stop-color: var(--svg-color--977ddd, #977DDD);
}

.lc952ppov {
  stop-color: var(--svg-color--b28afa, #B28AFA);
}

.li197rzkx {
  stop-color: var(--svg-color--55c3ff, #55C3FF);
}

.ltoxbabky {
  stop-color: var(--svg-color--ffff9f, #FFFF9F);
  stop-opacity: 0;
}

.lwmhkdbto {
  stop-color: var(--svg-color--5e97b1, #5E97B1);
  stop-opacity: 0;
}

.m--kmzbhi {
  d: path("M29.967 17.967c0 1.104-.905 1.979-1.988 2.197a10.01 10.01 0 0 0-7.815 7.815c-.218 1.083-1.093 1.988-2.197 1.988h-4c0-4.24 1.69-8.31 4.69-11.31s7.07-4.69 11.31-4.69z");
}

.ma48aem-o {
  stop-color: var(--svg-color--9970e2, #9970E2);
}

.mlp_qzbem {
  stop-color: var(--svg-color--ffef61, #FFEF61);
  stop-opacity: 0;
}

.o99gzfqhk {
  stop-color: var(--svg-color--977ddd, #977DDD);
  stop-opacity: 0;
}

.oolkibb9v {
  stop-color: var(--svg-color--ff677b, #FF677B);
  stop-opacity: 0;
}

.pre4sg_6z {
  stop-color: var(--svg-color--8569ca, #8569CA);
}

.q6y4jw46v {
  stop-color: var(--svg-color--60e4ab, #60E4AB);
}

.qlo3vv0nr {
  stop-color: var(--svg-color--ffef61, #FFEF61);
}

.qqix0q3zw {
  stop-color: var(--svg-color--ff4b5f, #FF4B5F);
}

.qwgybgbsx {
  stop-color: var(--svg-color--894fe0, #894FE0);
}

.rphqyf-xo {
  stop-color: var(--svg-color--6160ff, #6160FF);
  stop-opacity: 0;
}

.tde7r7b3t {
  stop-color: var(--svg-color--4d81f6, #4D81F6);
}

.tdnyvfbtw {
  stop-color: var(--svg-color--ffe38d, #FFE38D);
}

.th1b9wytg {
  stop-color: var(--svg-color--74ffb9, #74FFB9);
  stop-opacity: 0;
}

.u3aztubom {
  stop-color: var(--svg-color--46a0ff, #46A0FF);
}

.v8_-26bgx {
  stop-color: var(--svg-color--ffc751, #FFC751);
}

.veenggb3h {
  stop-color: var(--svg-color--f63ea0, #F63EA0);
}

.vfiar2bra {
  stop-color: var(--svg-color--74ffb9, #74FFB9);
}

.vtpyaebyy {
  stop-color: var(--svg-color--55c3ff, #55C3FF);
  stop-opacity: 0;
}

.w2q8jobqq {
  stop-color: var(--svg-color--ff9783, #FF9783);
}

.w9295jtdi {
  d: path("M29.967 17.967c0 1.104-.905 1.979-1.988 2.197a10.01 10.01 0 0 0-7.815 7.815c-.218 1.083-1.093 1.988-2.197 1.988h-10c0-5.83 2.32-11.43 6.44-15.56a22 22 0 0 1 15.56-6.44z");
}

.xm1ad5bjr {
  d: path("M29.967 17.967c0 1.104-.905 1.979-1.988 2.197a10.01 10.01 0 0 0-7.815 7.815c-.218 1.083-1.093 1.988-2.197 1.988h-7c0-5.04 2-9.87 5.56-13.44c3.56-3.56 8.4-5.56 13.44-5.56z");
}

.xt9395bxf {
  d: path("M29.967 18.717c0 .69-.563 1.242-1.248 1.327a10.005 10.005 0 0 0-8.675 8.675c-.085.685-.637 1.248-1.327 1.248h-1.75c0-3.45 1.37-6.76 3.81-9.19c2.44-2.44 5.75-3.81 9.19-3.81z");
}

.z4btr4bzo {
  stop-color: var(--svg-color--ff677b, #FF677B);
}

.zhmvymbwp {
  stop-color: var(--svg-color--894fe0, #894FE0);
  stop-opacity: 0;
}

.zy6mr92ve {
  stop-color: var(--svg-color--ffd05e, #FFD05E);
}

</style>
