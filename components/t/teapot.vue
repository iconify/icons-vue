<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ia18ogL)" clip-rule="evenodd" class="h3wfwrrhx"/><path fill="url(#ibfb22c)" clip-rule="evenodd" class="h3wfwrrhx"/><path fill="url(#iZFweVc)" clip-rule="evenodd" class="h3wfwrrhx"/><path fill="url(#iJJEOMc)" class="txf601b8u"/><path fill="url(#iW7fePd)" class="txf601b8u"/><path fill="url(#i7AQPZd)" class="lfdz_sbrw"/><path fill="url(#ipZiniG)" class="hsc_gvbkw"/><path class="cio-p0b6k"/><path fill="url(#i3GA80c)" class="hsc_gvbkw"/><path fill="url(#izQzbpe)" class="hsc_gvbkw"/><path fill="url(#i72He2b)" class="lgqw6dbqs"/><path fill="url(#iaF5oob)" class="lgqw6dbqs"/><path fill="url(#idTivIb)" class="lgqw6dbqs"/><path fill="url(#iQUhibb)" class="eh5y3bb-a"/><path fill="url(#iPCge3c)" class="eh5y3bb-a"/><path fill="url(#ifpGheb)" class="eh5y3bb-a"/><path fill="url(#iYF0m8f)" class="eh5y3bb-a"/><path fill="url(#inNtruR)" class="axfazacgy"/><path fill="url(#iAQI3hd)" class="axfazacgy"/><path fill="url(#itg7pHd)" class="axfazacgy"/><path fill="url(#i8jwvUb)" class="axfazacgy"/><path fill="url(#ikjE3Ne)" class="axfazacgy"/><path fill="url(#iWbsizb)" class="axfazacgy"/><defs><radialGradient id="ibfb22c" cx="0" cy="0" r="1" gradientTransform="rotate(121.487 7.74 16.16)scale(5.86335 4.5261)" gradientUnits="userSpaceOnUse"><stop offset=".631" class="j1upakjtg"/><stop offset=".72" class="mqbg-6bpu"/><stop offset="1" class="w0264ibnb"/></radialGradient><radialGradient id="iJJEOMc" cx="0" cy="0" r="1" gradientTransform="translate(17.974 3.461)scale(6.0573)" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></radialGradient><radialGradient id="iW7fePd" cx="0" cy="0" r="1" gradientTransform="rotate(114.057 6.106 8.246)scale(1.91647)" gradientUnits="userSpaceOnUse"><stop class="sm3gmy1-u"/><stop offset=".666" class="bqev1z1fg"/></radialGradient><radialGradient id="i7AQPZd" cx="0" cy="0" r="1" gradientTransform="rotate(95.102 5.55 12.193)scale(3.51392 15.3676)" gradientUnits="userSpaceOnUse"><stop class="guphi-b-n"/><stop offset=".691" class="xi_fzgg9z"/></radialGradient><radialGradient id="i3GA80c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.1875 -2.25924 0 5.813 12.688)" gradientUnits="userSpaceOnUse"><stop offset=".386" class="ju3kvxbyd"/><stop offset=".735" class="fcujf6h_j"/><stop offset="1" class="e3z5wm28c"/></radialGradient><radialGradient id="izQzbpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.5 -5.0325 0 8.72 19.188)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="u1cendbxm"/><stop offset="1" class="j4hbaqbhl"/></radialGradient><radialGradient id="iaF5oob" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46875 -6.625 0 20.906 10.031)" gradientUnits="userSpaceOnUse"><stop class="jdy8s8-td"/><stop offset="1" class="l5tl4dbsk"/></radialGradient><radialGradient id="idTivIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78125 -5.63616 0 6.469 10)" gradientUnits="userSpaceOnUse"><stop class="mqjcnvb_l"/><stop offset="1" class="p-em9cciq"/></radialGradient><radialGradient id="iQUhibb" cx="0" cy="0" r="1" gradientTransform="matrix(-13.375 1.3751 -1.5401 -14.97994 19.75 15.625)" gradientUnits="userSpaceOnUse"><stop class="q6u2hac1o"/><stop offset=".5" class="hqfpfdbas"/><stop offset=".969" class="l6kfjjbxl"/></radialGradient><radialGradient id="iPCge3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.875 -23.8281 0 15.44 29)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="h82bdjw0x"/><stop offset="1" class="z59-lrb4u"/></radialGradient><radialGradient id="ifpGheb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.25 20.25002 -15.1328 -3.17602 16.875 18.5)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="ul9cqbfuk"/><stop offset=".707" class="co_wk9uvv"/></radialGradient><radialGradient id="i8jwvUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .42188 -4.41051 0 18.031 29.281)" gradientUnits="userSpaceOnUse"><stop class="alo-9vb9n"/><stop offset="1" class="z2eo5d06e"/></radialGradient><radialGradient id="ikjE3Ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.0625 -4.875 0 8.688 28.813)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="ewyg61bnb"/><stop offset="1" class="wg6k-sb8s"/></radialGradient><linearGradient id="ia18ogL" x1="29.063" x2="24.41" y1="13.563" y2="23" gradientUnits="userSpaceOnUse"><stop class="xgp72zh7p"/><stop offset="1" class="cmu4q8b3c"/></linearGradient><linearGradient id="iZFweVc" x1="23" x2="30" y1="19.688" y2="15.625" gradientUnits="userSpaceOnUse"><stop class="kn5tw6bqh"/><stop offset=".756" class="r4gmuabee"/></linearGradient><linearGradient id="ipZiniG" x1="12.126" x2="-3.802" y1="24.628" y2="7.484" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="i72He2b" x1="7" x2="24.011" y1="10.25" y2="10.25" gradientUnits="userSpaceOnUse"><stop class="qqr449b1c"/><stop offset=".342" class="irll60bhb"/><stop offset=".658" class="rq2ilgbiy"/><stop offset="1" class="ynlnkmbzw"/></linearGradient><linearGradient id="iYF0m8f" x1="15.44" x2="15.44" y1="11" y2="11.625" gradientUnits="userSpaceOnUse"><stop class="vza2xqbkp"/><stop offset="1" class="zqh9lgn3y"/></linearGradient><linearGradient id="inNtruR" x1="15.472" x2="15.472" y1="24.357" y2="31.614" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="iAQI3hd" x1="10.313" x2="21.044" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="aj0zdof9b"/><stop offset=".536" class="qdooqbbzy"/><stop offset="1" class="ihvjqm3uj"/></linearGradient><linearGradient id="itg7pHd" x1="15.473" x2="15.473" y1="28" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".688" class="br00ff_xl"/><stop offset=".906" class="x6gm18bpb"/></linearGradient><linearGradient id="iWbsizb" x1="15.473" x2="15.473" y1="28" y2="30" gradientUnits="userSpaceOnUse"><stop class="gtlvifbdb"/><stop offset=".117" class="x4n7kqbxm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:teapot" /></template>
<style>
.aj0zdof9b {
  stop-color: var(--svg-color--ce1d4a, #CE1D4A);
}

.alo-9vb9n {
  stop-color: var(--svg-color--ff6998, #FF6998);
}

.axfazacgy {
  d: path("m20.86 28.94l-.97-.94h-8.83l-.97.94c-.4.39-.12 1.06.43 1.06h9.91c.55 0 .82-.67.43-1.06");
}

.bqev1z1fg {
  stop-color: var(--svg-color--de3457, #DE3457);
}

.br00ff_xl {
  stop-color: var(--svg-color--e52988, #E52988);
  stop-opacity: 0;
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.cio-p0b6k {
  fill: var(--svg-color--d42e6b, #D42E6B);
  d: path("M8.72 26.43L4.5 22.42A8.04 8.04 0 0 1 2 16.59v-5.06c0-.29.24-.53.53-.53h2.29c.29 0 .53.24.53.53v2.11c0 .49.27.94.7 1.16l2.66 1.4v10.23z");
}

.cmu4q8b3c {
  stop-color: var(--svg-color--e5265d, #E5265D);
}

.co_wk9uvv {
  stop-color: var(--svg-color--d45673, #D45673);
}

.e3z5wm28c {
  stop-color: var(--svg-color--d74273, #D74273);
  stop-opacity: 0;
}

.eh5y3bb-a {
  d: path("M24.81 15.2c-.04-.1-.08-.19-.12-.29L23.06 11H7.82l-1.63 3.92c-.04.09-.08.19-.12.28v.01c-.46 1.15-.71 2.4-.71 3.72C5.36 24.49 9.87 29 15.44 29s10.08-4.51 10.08-10.08c0-1.31-.25-2.57-.71-3.72");
}

.ewyg61bnb {
  stop-color: var(--svg-color--d36170, #D36170);
}

.fcujf6h_j {
  stop-color: var(--svg-color--d74273, #D74273);
}

.ft5dv1b6b {
  fill: none;
}

.gtlvifbdb {
  stop-color: var(--svg-color--d3094d, #D3094D);
}

.guphi-b-n {
  stop-color: var(--svg-color--ef5e85, #EF5E85);
}

.h3wfwrrhx {
  fill-rule: evenodd;
  d: path("M26.27 13A3.73 3.73 0 0 1 30 16.73c0 3.46-2.81 6.27-6.27 6.27h-4.91l4.14-7.98A3.73 3.73 0 0 1 26.27 13M28 16.73c0-.95-.78-1.73-1.73-1.73c-.65 0-1.24.36-1.54.93L22.11 21h1.62A4.28 4.28 0 0 0 28 16.73");
}

.h82bdjw0x {
  stop-color: var(--svg-color--e31f8d, #E31F8D);
}

.hqfpfdbas {
  stop-color: var(--svg-color--f32d60, #F32D60);
}

.hsc_gvbkw {
  d: path("M8.72 26.43L4.5 22.42A8.04 8.04 0 0 1 2 16.59v-5.06c0-.29.24-.53.53-.53h2.29c.29 0 .53.24.53.53v2.11c0 .49.27.94.7 1.16l2.66 1.4v10.23z");
}

.ihvjqm3uj {
  stop-color: var(--svg-color--fe3074, #FE3074);
}

.irll60bhb {
  stop-color: var(--svg-color--f4542b, #F4542B);
}

.j1upakjtg {
  stop-color: var(--svg-color--ff66a2, #FF66A2);
  stop-opacity: 0;
}

.j4hbaqbhl {
  stop-color: var(--svg-color--c21d46, #C21D46);
  stop-opacity: 0;
}

.jdy8s8-td {
  stop-color: var(--svg-color--ff975c, #FF975C);
}

.ju3kvxbyd {
  stop-color: var(--svg-color--c5174a, #C5174A);
}

.kmmuo7biq {
  stop-color: var(--svg-color--ed1452, #ED1452);
}

.kn5tw6bqh {
  stop-color: var(--svg-color--e92942, #E92942);
}

.l5tl4dbsk {
  stop-color: var(--svg-color--ff9b5c, #FF9B5C);
  stop-opacity: 0;
}

.l6kfjjbxl {
  stop-color: var(--svg-color--de385c, #DE385C);
}

.lfdz_sbrw {
  d: path("M22.07 10c-1.59-1.84-3.94-3-6.56-3s-4.97 1.16-6.56 3z");
}

.lgqw6dbqs {
  d: path("M23.26 9.5H7.75c-.41 0-.75.34-.75.75s.34.75.75.75h15.51c.41 0 .75-.34.75-.75s-.34-.75-.75-.75");
}

.mqbg-6bpu {
  stop-color: var(--svg-color--ff65a0, #FF65A0);
}

.mqjcnvb_l {
  stop-color: var(--svg-color--db6d60, #DB6D60);
}

.p-em9cciq {
  stop-color: var(--svg-color--db7065, #DB7065);
  stop-opacity: 0;
}

.q6u2hac1o {
  stop-color: var(--svg-color--ff668e, #FF668E);
}

.qdooqbbzy {
  stop-color: var(--svg-color--f8186a, #F8186A);
}

.qqr449b1c {
  stop-color: var(--svg-color--e04539, #E04539);
}

.r4gmuabee {
  stop-color: var(--svg-color--eb2641, #EB2641);
  stop-opacity: 0;
}

.rq2ilgbiy {
  stop-color: var(--svg-color--ff673f, #FF673F);
}

.sm3gmy1-u {
  stop-color: var(--svg-color--ff5f8b, #FF5F8B);
}

.txf601b8u {
  d: path("M15.51 7.98a1.49 1.49 0 1 0 0-2.98a1.49 1.49 0 0 0 0 2.98");
}

.u1cendbxm {
  stop-color: var(--svg-color--c12146, #C12146);
}

.ul9cqbfuk {
  stop-color: var(--svg-color--cf4d5f, #CF4D5F);
  stop-opacity: 0;
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.vza2xqbkp {
  stop-color: var(--svg-color--e7123d, #E7123D);
}

.w0264ibnb {
  stop-color: var(--svg-color--ff65a0, #FF65A0);
  stop-opacity: 0;
}

.wg6k-sb8s {
  stop-color: var(--svg-color--cc6974, #CC6974);
  stop-opacity: 0;
}

.x4n7kqbxm {
  stop-color: var(--svg-color--ce0e49, #CE0E49);
  stop-opacity: 0;
}

.x6gm18bpb {
  stop-color: var(--svg-color--e72989, #E72989);
}

.xgp72zh7p {
  stop-color: var(--svg-color--f72289, #F72289);
}

.xi_fzgg9z {
  stop-color: var(--svg-color--e73564, #E73564);
}

.ynlnkmbzw {
  stop-color: var(--svg-color--ff8e36, #FF8E36);
}

.z2eo5d06e {
  stop-color: var(--svg-color--ff6797, #FF6797);
  stop-opacity: 0;
}

.z59-lrb4u {
  stop-color: var(--svg-color--e3208b, #E3208B);
  stop-opacity: 0;
}

.zqh9lgn3y {
  stop-color: var(--svg-color--ff2249, #FF2249);
  stop-opacity: 0;
}

</style>
