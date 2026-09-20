<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVG3Vp0RdWB" cx="64.926" cy="83.292" r="90.99" gradientUnits="userSpaceOnUse"><stop offset=".24" class="ztgl8tffm"/><stop offset=".356" class="atqcy3bua"/><stop offset=".477" class="qkuxbacng"/><stop offset=".601" class="zdnfbkr4w"/><stop offset=".601" class="zdnfbkr4w"/><stop offset=".676" class="yhsm0dith"/><stop offset=".829" class="imi4m4byv"/><stop offset=".964" class="p3bo03bmf"/></radialGradient><path fill="url(#SVG3Vp0RdWB)" class="ajztvtzjj"/><path class="q8mtj9h1j"/><path class="zaz9ktfkx"/><radialGradient id="SVGHt136dxR" cx="42.163" cy="79.187" r="51.929" gradientUnits="userSpaceOnUse"><stop offset=".273" class="dprfjnfgi"/><stop offset=".377" class="kdw8q_yuz"/><stop offset=".537" class="fnb837s-h"/><stop offset=".695" class="nv940xd_y"/><stop offset=".791" class="i5ts85xnx"/></radialGradient><path fill="url(#SVGHt136dxR)" class="xgq4jxg9h"/><radialGradient id="SVGT6BfbeqG" cx="42.434" cy="73.75" r="49.587" gradientUnits="userSpaceOnUse"><stop offset=".273" class="dprfjnfgi"/><stop offset=".377" class="kdw8q_yuz"/><stop offset=".537" class="fnb837s-h"/><stop offset=".695" class="nv940xd_y"/><stop offset=".94" class="i5ts85xnx"/></radialGradient><path fill="url(#SVGT6BfbeqG)" class="lb1849_ge"/><radialGradient id="SVGAJas8cFg" cx="48.143" cy="67.226" r="59.275" gradientUnits="userSpaceOnUse"><stop offset=".273" class="dprfjnfgi"/><stop offset=".377" class="kdw8q_yuz"/><stop offset=".537" class="fnb837s-h"/><stop offset=".695" class="nv940xd_y"/><stop offset=".94" class="i5ts85xnx"/></radialGradient><path fill="url(#SVGAJas8cFg)" class="t6g575pew"/><radialGradient id="SVGr0bTbdbm" cx="52.764" cy="63.692" r="61.031" gradientUnits="userSpaceOnUse"><stop offset=".273" class="dprfjnfgi"/><stop offset=".377" class="kdw8q_yuz"/><stop offset=".537" class="fnb837s-h"/><stop offset=".695" class="nv940xd_y"/><stop offset=".94" class="i5ts85xnx"/></radialGradient><path fill="url(#SVGr0bTbdbm)" class="xee59fblj"/><radialGradient id="SVGCF1f7WDI" cx="58.745" cy="60.702" r="60.068" gradientUnits="userSpaceOnUse"><stop offset=".273" class="dprfjnfgi"/><stop offset=".377" class="kdw8q_yuz"/><stop offset=".537" class="fnb837s-h"/><stop offset=".695" class="nv940xd_y"/><stop offset=".94" class="i5ts85xnx"/></radialGradient><path fill="url(#SVGCF1f7WDI)" class="oixw-bc-c"/><radialGradient id="SVGammU1bfm" cx="65.813" cy="59.614" r="59.278" gradientUnits="userSpaceOnUse"><stop offset=".273" class="dprfjnfgi"/><stop offset=".377" class="kdw8q_yuz"/><stop offset=".537" class="fnb837s-h"/><stop offset=".695" class="nv940xd_y"/><stop offset=".94" class="i5ts85xnx"/></radialGradient><path fill="url(#SVGammU1bfm)" class="yj8w2699i"/><radialGradient id="SVGodTq6rIl" cx="72.992" cy="59.794" r="58.103" gradientUnits="userSpaceOnUse"><stop offset=".273" class="dprfjnfgi"/><stop offset=".377" class="kdw8q_yuz"/><stop offset=".537" class="fnb837s-h"/><stop offset=".695" class="nv940xd_y"/><stop offset=".94" class="i5ts85xnx"/></radialGradient><path fill="url(#SVGodTq6rIl)" class="u17iwtbtr"/><radialGradient id="SVGNDb17brR" cx="78.59" cy="63.148" r="61.898" gradientUnits="userSpaceOnUse"><stop offset=".273" class="dprfjnfgi"/><stop offset=".377" class="kdw8q_yuz"/><stop offset=".537" class="fnb837s-h"/><stop offset=".695" class="nv940xd_y"/><stop offset=".94" class="i5ts85xnx"/></radialGradient><path fill="url(#SVGNDb17brR)" class="i1k5kvbhl"/><radialGradient id="SVGH7OiRcih" cx="84.57" cy="67.77" r="57.742" gradientUnits="userSpaceOnUse"><stop offset=".273" class="dprfjnfgi"/><stop offset=".363" class="kdw8q_yuz"/><stop offset=".502" class="fnb837s-h"/><stop offset=".639" class="nv940xd_y"/><stop offset=".94" class="i5ts85xnx"/></radialGradient><path fill="url(#SVGH7OiRcih)" class="nr7kc3byh"/><radialGradient id="SVGmCChBcwo" cx="90.007" cy="74.566" r="39.313" gradientUnits="userSpaceOnUse"><stop offset=".273" class="dprfjnfgi"/><stop offset=".384" class="kdw8q_yuz"/><stop offset=".553" class="fnb837s-h"/><stop offset=".721" class="nv940xd_y"/><stop offset=".94" class="i5ts85xnx"/></radialGradient><path fill="url(#SVGmCChBcwo)" class="gpthfkbne"/><radialGradient id="SVG9uJffcXq" cx="93.269" cy="79.187" r="39.252" gradientUnits="userSpaceOnUse"><stop offset=".483" class="dprfjnfgi"/><stop offset=".556" class="kdw8q_yuz"/><stop offset=".668" class="fnb837s-h"/><stop offset=".779" class="nv940xd_y"/><stop offset=".94" class="i5ts85xnx"/></radialGradient><path fill="url(#SVG9uJffcXq)" class="fepa6hbpn"/><radialGradient id="SVG6sHxnbNw" cx="67.049" cy="66.672" r="64.015" gradientTransform="matrix(-.0102 .9999 -1.1205 -.0114 142.434 .386)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="zgg6bublq"/><stop offset=".532" class="kooczt4pk"/><stop offset=".678" class="sqo5bobwd"/><stop offset="1" class="id8etabjw"/></radialGradient><path fill="url(#SVG6sHxnbNw)" class="q0_ke8ofy"/><path class="ofbfnlbzj"/><radialGradient id="SVGhJOyIbZN" cx="66.091" cy="85.51" r="39.018" gradientUnits="userSpaceOnUse"><stop offset=".424" class="wdaygginz"/><stop offset=".484" class="awjiuccpz"/><stop offset=".589" class="c8nyqzv0o"/><stop offset=".703" class="pq36b6t_l"/><stop offset=".831" class="to6l-nb5l"/><stop offset="1" class="ngh3whblw"/></radialGradient><path fill="url(#SVGhJOyIbZN)" class="glovcvb7b"/><radialGradient id="SVGFuF0Tdte" cx="62.651" cy="73.869" r="41.866" fx="62.599" fy="73.861" gradientUnits="userSpaceOnUse"><stop offset=".58" class="wdaygginz"/><stop offset=".66" class="jk1ibrbtl"/><stop offset=".757" class="ko5-e96nx"/><stop offset=".863" class="emlwgubrv"/><stop offset=".943" class="ngh3whblw"/></radialGradient><path fill="url(#SVGFuF0Tdte)" class="de_uypb4m"/><radialGradient id="SVGr2hYFeXf" cx="68.766" cy="82.04" r="41.484" gradientTransform="matrix(.5397 .8418 -1.275 .8175 136.255 -42.917)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="wdaygginz"/><stop offset=".263" class="k3x87abww"/><stop offset=".453" class="dp91bq9_o"/><stop offset=".655" class="lai_-6yps"/><stop offset=".831" class="ngh3whblw"/></radialGradient><path fill="url(#SVGr2hYFeXf)" class="nxh83mxhh"/><path class="n8q5hkbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:sunrise-over-mountains" /></template>
<style>
.ajztvtzjj {
  d: path("M124.15 11.44c0-4.15-3.37-7.52-7.52-7.52H11.32c-4.15 0-7.52 3.37-7.52 7.52v105.3c0 4.15 3.37 7.52 7.52 7.52h105.3c4.15 0 7.52-3.37 7.52-7.52V11.44z");
}

.atqcy3bua {
  stop-color: var(--svg-color--fca330, #fca330);
}

.awjiuccpz {
  stop-color: var(--svg-color--713035, #713035);
}

.c8nyqzv0o {
  stop-color: var(--svg-color--5b2a33, #5b2a33);
}

.de_uypb4m {
  d: path("M40.67 94.1c-2.28-2.85-4.36-6.77-6.54-9.41s-2.64-4.13-2.41-5.74s2.3-.34 3.44.34c1.15.69 4.92 2.88 7.91 8.05s3.8 8.02 4.38 8.6s2.07 1.61 3.56 4.02s6.54 11.94 6.08 12.63s-7.46-2.3-10.45-4.71s-4.13-5.4-4.59-7.46c-.46-2.07 0-4.59-1.38-6.32");
}

.dp91bq9_o {
  stop-color: var(--svg-color--6f2f35, #6f2f35);
}

.dprfjnfgi {
  stop-color: var(--svg-color--ffc618, #ffc618);
}

.emlwgubrv {
  stop-color: var(--svg-color--562832, #562832);
}

.fepa6hbpn {
  d: path("m94.89 79.67l29.25 6.06s.02-7.7 0-18.15z");
}

.fnb837s-h {
  stop-color: var(--svg-color--fca929, #fca929);
}

.glovcvb7b {
  d: path("M29.51 124.26s-.78-6.62-.89-8.34s-.34-5.28-.92-9.07c-.57-3.79-1.61-9.18-1.15-11.02s2.53-2.87 3.79-2.76s5.17 3.1 6.54 6.08c1.38 2.99 3.79 11.6 5.63 13.2c1.84 1.61 5.74 3.56 7.23 4.25s3.44.8 4.36 1.95s1.03 2.18 1.84 2.99s2.24 2.72 2.24 2.72z");
}

.gpthfkbne {
  d: path("M124.14 57.5c.04-4.19.01-8.72 0-12.84L89.16 72.34c1.14 2.13 1.8 4.02 2.15 5.24z");
}

.i1k5kvbhl {
  d: path("M116.34 3.91c-3.18-.04-10.92-.01-12.14 0L78.02 61.3c1.72.87 3.2 1.9 4.52 3z");
}

.i5ts85xnx {
  stop-color: var(--svg-color--f98d39, #f98d39);
  stop-opacity: 0;
}

.id8etabjw {
  stop-color: var(--svg-color--4d242c, #4d242c);
}

.imi4m4byv {
  stop-color: var(--svg-color--a96f86, #a96f86);
}

.jk1ibrbtl {
  stop-color: var(--svg-color--7d3336, #7d3336);
}

.k3x87abww {
  stop-color: var(--svg-color--7d3337, #7d3337);
}

.kdw8q_yuz {
  stop-color: var(--svg-color--febe1d, #febe1d);
}

.ko5-e96nx {
  stop-color: var(--svg-color--6e2f35, #6e2f35);
}

.kooczt4pk {
  stop-color: var(--svg-color--bb595a, #bb595a);
}

.lai_-6yps {
  stop-color: var(--svg-color--582933, #582933);
}

.lb1849_ge {
  d: path("M3.8 41.71c0 4.36.01 9.05 0 13.63l36.71 20.22c.43-1.11 1.05-2.49 1.93-3.98z");
}

.n8q5hkbrs {
  fill: var(--svg-color--3e2230, #3e2230);
  d: path("M10.4 124.21a7.517 7.517 0 0 1-6.6-7.47v-23.3s2.08-1.45 4.37-4.86s4.92-7.94 5.86-8.93c1.17-1.22 3.73-1.3 4.18-.77c.67.77.15 2.58-.15 3.66c-.24.84-1.17 4.8-1.6 6.97s-.54 8.75-1.34 13.52c-.81 4.77-1.76 12.22-2.63 14.76s-1.84 6.02-2.09 6.42");
}

.ngh3whblw {
  stop-color: var(--svg-color--3e2230, #3e2230);
}

.nr7kc3byh {
  d: path("M124.16 32.64c-.02-9.06 0-16.87 0-18.01L84.28 65.87c.33.33.66.66.97.99c.97 1.04 1.8 2.1 2.51 3.15z");
}

.nv940xd_y {
  stop-color: var(--svg-color--f98d39, #f98d39);
}

.nxh83mxhh {
  d: path("M59.15 105.93c-.73 1.24.69 3.1 1.95 4.71s3.1 5.51 3.1 5.51s-.92 4.25.69 4.94s4.82-2.87 6.77-4.94s4.59-5.05 5.63-7.81c1.03-2.76 2.76-6.77 4.71-9.07s4.25-3.44 5.51-5.51s2.3-5.97 2.3-5.97s3.9-1.72 3.67-4.82s-6.2 4.25-8.15 6.66s-2.87 3.21-4.59 4.36s-2.76 1.61-2.76 1.61s-3.56 2.53-4.02 3.33s-4.59 11.6-4.59 11.6s-8.72-7.13-10.22-4.6");
}

.ofbfnlbzj {
  fill: var(--svg-color--3e2230, #3e2230);
  d: path("M92.79 104.09s-3.56 1.72-5.63 3.44s-5.17 6.08-7.12 9.07s-3.1 6.43-3.1 6.43l-.5 1.22h24.63s2.16-11.21 2.39-16.61s1.38-17.45 1.61-19.63s1.38-5.86-.23-5.86s-2.53 3.79-3.9 5.17c-1.38 1.38-4.13 2.53-5.05 4.25c-.92 1.73-3.1 12.52-3.1 12.52");
}

.oixw-bc-c {
  d: path("M50.67 3.91c-4.35.01-8.29-.01-11.48 0l16.95 56.33c1.58-.56 3.3-1.01 5.17-1.29z");
}

.p3bo03bmf {
  stop-color: var(--svg-color--7362ad, #7362ad);
}

.pq36b6t_l {
  stop-color: var(--svg-color--4b2531, #4b2531);
}

.q0_ke8ofy {
  d: path("M3.8 80.55v36.19c0 4.15 3.37 7.52 7.52 7.52h105.3c4.15 0 7.52-3.37 7.52-7.52V79.02s-3.95-2.87-5.3-4.8s-5.8-5.8-10.64-5.61c-4.83.19-9.67 2.71-11.99 4.45s-4.25 3.67-7.16 5.22c-2.9 1.55-10.83 8.51-14.89 12.76s-8.32 8.51-8.32 8.51s-8.51-11.8-13.92-17.02c-5.42-5.22-8.32-7.35-11.02-7.54c-2.71-.19-3.35.78-3.35.78s-5.67-9.95-9.45-12.09s-8.94-1.01-9.95-.63s-6.51 5.03-8.44 7.56c-3.26 4.28-5.91 9.94-5.91 9.94");
}

.q8mtj9h1j {
  fill: var(--svg-color--fff7b3, #fff7b3);
  d: path("M66.3 60.78c14.71.12 23.79 11.28 24.16 25.14s-10.18 24.4-25.38 24.4c-13 0-23.92-11.02-23.54-27.22c.23-10.55 9.15-22.45 24.76-22.32");
}

.qkuxbacng {
  stop-color: var(--svg-color--f9963b, #f9963b);
}

.sqo5bobwd {
  stop-color: var(--svg-color--7a3d5c, #7a3d5c);
}

.t6g575pew {
  d: path("M4.53 10.57c-.94 1.99-.73 7.25-.74 11.98c0 .95-.01 2.79 0 4.85l39.85 42.34c.61-.86 1.29-1.73 2.09-2.59c.55-.59 1.15-1.19 1.8-1.78z");
}

.to6l-nb5l {
  stop-color: var(--svg-color--412330, #412330);
}

.u17iwtbtr {
  d: path("M93.57 3.91c-3.3 0-6.99.01-10.9.01L70.79 58.98c1.95.31 3.7.81 5.29 1.44z");
}

.wdaygginz {
  stop-color: var(--svg-color--823437, #823437);
}

.xee59fblj {
  d: path("M28.26 3.92c-4.82-.01-10.04.01-14.3 0L49.59 63.7c1.32-.97 2.83-1.87 4.52-2.64z");
}

.xgq4jxg9h {
  d: path("M3.8 64.78c-.02 9.74 0 17.25 0 17.25l35.89-3.83s0-.02.01-.07z");
}

.yhsm0dith {
  stop-color: var(--svg-color--e07c5e, #e07c5e);
}

.yj8w2699i {
  d: path("M72.31 3.91h-11L63.4 58.7c.86-.07 1.75-.11 2.68-.1c.99 0 1.92.06 2.82.14z");
}

.zaz9ktfkx {
  fill: var(--svg-color--fffffc, #fffffc);
  d: path("M49.94 72.28c-2.26 3.31-4.55 7.58-1.44 9.49c2.68 1.65 4.88-2.41 6.74-4.95c1.86-2.55 5.71-6.12 3.1-8.39c-1.78-1.55-5.44-.49-8.4 3.85");
}

.zdnfbkr4w {
  stop-color: var(--svg-color--f5814e, #f5814e);
}

.zgg6bublq {
  stop-color: var(--svg-color--cd6159, #cd6159);
}

.ztgl8tffm {
  stop-color: var(--svg-color--fda72c, #fda72c);
}

</style>
