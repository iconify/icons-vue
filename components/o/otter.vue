<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iE8lpFZ)" class="uvq-lrb2i"/><path fill="url(#ieJVxDb)" class="uvq-lrb2i"/><g filter="url(#iBxtAEM)"><path class="pv7vaoa5k"/><path fill="url(#ibkuZJc)" class="cotncwbxg"/></g><circle fill="url(#iVGe4HW)" class="nqx299b1l"/><circle fill="url(#i9Y2FbZ)" class="hy5cs1gce"/><circle fill="url(#iUeWTCd)" class="hy5cs1gce"/><path class="zgj8xvbdy"/><path fill="url(#i2gxm4b)" class="o9_ekcbfi"/><path fill="url(#ifBG60c)" class="o9_ekcbfi"/><path fill="url(#iqE64Bb)" class="o9_ekcbfi"/><path fill="url(#ivOfUhb)" class="o9_ekcbfi"/><path fill="url(#iwTYTdb)" class="o9_ekcbfi"/><path fill="url(#iD0sCUU)" class="o9_ekcbfi"/><path fill="url(#i6FZBeb)" class="inks3jb8f"/><path fill="url(#iqkHOZf)" class="o9_ekcbfi"/><path fill="url(#iajmi1b)" class="o9_ekcbfi"/><path fill="url(#ihIjVAc)" class="o9_ekcbfi"/><g filter="url(#iXUmtLb)"><circle class="mcwwoxy4j"/></g><path fill="url(#isIaWNe)" class="rvbm7mbnx"/><path fill="url(#iGRtzyd)" class="rvbm7mbnx"/><path fill="url(#ixYv0rc)" class="rvbm7mbnx"/><path fill="url(#i6wblnc)" class="vmh73wzcg"/><path fill="url(#ifjUtPd)" class="vmh73wzcg"/><path fill="url(#ib4nc9d)" class="vmh73wzcg"/><path fill="url(#iwpKZ9b)" class="ftxg8rssm"/><path fill="url(#iFsyjQb)" class="ftxg8rssm"/><path class="z4s2w9nul"/><path fill="url(#irwDXjC)" class="bjsaxbbek"/><path fill="url(#i74R5Kd)" class="bjsaxbbek"/><path class="kilc9osws"/><path fill="url(#ieTRoac)" class="tpcciqdof"/><path fill="url(#iUBRzLe)" class="tpcciqdof"/><path fill="url(#iughEVN)" class="tpcciqdof"/><path fill="url(#i6bRqrc)" class="tpcciqdof"/><path fill="url(#ixyf7VS)" class="hhq5fhbhd"/><path fill="url(#ivJUYoe)" class="hhq5fhbhd"/><path fill="url(#iSKgSCc)" class="hhq5fhbhd"/><path clip-rule="evenodd" class="w7csafb9y"/><path fill="url(#i2HnHqc)" clip-rule="evenodd" class="j5g4f5fzp"/><path fill="url(#iIM8YLc)" clip-rule="evenodd" class="j5g4f5fzp"/><path fill="url(#iB0hGSc)" clip-rule="evenodd" class="j5g4f5fzp"/><path fill="url(#io6TTRu)" clip-rule="evenodd" class="c-d-yqgeb"/><g filter="url(#iBGm97d)"><path stroke="url(#ilWlRVp)" class="y7aejbcai"/></g><g filter="url(#iQVH2kb)"><path stroke="url(#iwLZ4DU)" class="cwteddcxz"/></g><defs><radialGradient id="iE8lpFZ" cx="0" cy="0" r="1" gradientTransform="rotate(134.864 3.562 11.328)scale(1.6289 1.35706)" gradientUnits="userSpaceOnUse"><stop class="i-kow0--d"/><stop offset="1" class="h99mlrh7q"/></radialGradient><radialGradient id="ieJVxDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.88374 1.4375 -1.65342 -1.01647 13.839 17.009)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="blzybplow"/><stop offset="1" class="r2nehz-yy"/></radialGradient><radialGradient id="ibkuZJc" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -2.32792 3.18749 2.95243 17.495 18.72)" gradientUnits="userSpaceOnUse"><stop class="lcjgqb7wo"/><stop offset="1" class="pa1kjdjbv"/></radialGradient><radialGradient id="iVGe4HW" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23438 1.29687 -1.08044 -1.02839 11.823 10.15)" gradientUnits="userSpaceOnUse"><stop class="i-kow0--d"/><stop offset="1" class="h99mlrh7q"/></radialGradient><radialGradient id="i9Y2FbZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41843 1.23437 -.5338 -.6134 4.21 9.836)" gradientUnits="userSpaceOnUse"><stop class="i-kow0--d"/><stop offset="1" class="h99mlrh7q"/></radialGradient><radialGradient id="iUeWTCd" cx="0" cy="0" r="1" gradientTransform="rotate(106.504 -2.1 6.507)scale(1.76002 1.6111)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="blzybplow"/><stop offset="1" class="r2nehz-yy"/></radialGradient><radialGradient id="ivOfUhb" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 1.125 -1.69404 1.7411 3.386 10.759)" gradientUnits="userSpaceOnUse"><stop class="n6iszy2th"/><stop offset="1" class="oy2694bda"/></radialGradient><radialGradient id="iwTYTdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 .09375 -.196 -1.69869 9.073 18.962)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="fr9uvvbni"/><stop offset="1" class="zimrksbbk"/></radialGradient><radialGradient id="iD0sCUU" cx="0" cy="0" r="1" gradientTransform="matrix(2.62646 5.64697 -6.32678 2.94265 17.633 15.805)" gradientUnits="userSpaceOnUse"><stop class="foqbprdif"/><stop offset="1" class="oj7susspq"/></radialGradient><radialGradient id="i6FZBeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.27997 -.97278 0 23.89 15.432)" gradientUnits="userSpaceOnUse"><stop class="xvvr0ibxu"/><stop offset="1" class="pyvm_yb8a"/></radialGradient><radialGradient id="iqkHOZf" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90773 14.24831 -15.96356 -8.85967 29.413 9.134)" gradientUnits="userSpaceOnUse"><stop class="pd0fkd17h"/><stop offset="1" class="dp37m6sqm"/></radialGradient><radialGradient id="iajmi1b" cx="0" cy="0" r="1" gradientTransform="rotate(163.735 11.617 9.166)scale(.77275 1.91076)" gradientUnits="userSpaceOnUse"><stop class="x2hd0sbwb"/><stop offset=".788" class="u57yu_b2x"/></radialGradient><radialGradient id="ihIjVAc" cx="0" cy="0" r="1" gradientTransform="rotate(33.153 .509 32.48)scale(5.74504 14.2056)" gradientUnits="userSpaceOnUse"><stop class="x2hd0sbwb"/><stop offset="1" class="u57yu_b2x"/></radialGradient><radialGradient id="isIaWNe" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 9.803 14.3)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iGRtzyd" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 2.144 9.074)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="i6wblnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 4.523 14.3)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="ifjUtPd" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 -.496 8.051)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iFsyjQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10804 1.14636 -2.23323 -.21047 10.653 20.604)" gradientUnits="userSpaceOnUse"><stop class="tsq6q82xq"/><stop offset="1" class="zex8bmbii"/></radialGradient><radialGradient id="irwDXjC" cx="0" cy="0" r="1" gradientTransform="rotate(114.465 1.009 12.366)scale(4.60292)" gradientUnits="userSpaceOnUse"><stop offset=".417" class="d47hqgble"/><stop offset="1" class="k6t69jqpd"/></radialGradient><radialGradient id="i74R5Kd" cx="0" cy="0" r="1" gradientTransform="rotate(-44.363 31.229 -3.283)scale(1.98886 2.71704)" gradientUnits="userSpaceOnUse"><stop class="jsxd41bok"/><stop offset="1" class="npqnkx3xy"/></radialGradient><radialGradient id="iUBRzLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.35937 3.26539 0 6.991 17.978)" gradientUnits="userSpaceOnUse"><stop class="owego8bwu"/><stop offset="1" class="bw3h0_6sg"/></radialGradient><radialGradient id="i6bRqrc" cx="0" cy="0" r="1" gradientTransform="rotate(132.614 .089 8.942)scale(1.06158 1.46427)" gradientUnits="userSpaceOnUse"><stop class="zpyhqtffa"/><stop offset="1" class="xfot5fv0n"/></radialGradient><radialGradient id="ixyf7VS" cx="0" cy="0" r="1" gradientTransform="rotate(125.838 -.124 9.137)scale(.9159 .81656)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="ivJUYoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.35063 .31968 -.28124 -.30847 7.262 14.634)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="i2HnHqc" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 2.5 -5.23994 2.29248 8.651 19.603)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="wnt7mdb7l"/><stop offset="1" class="hd3dwm1lf"/></radialGradient><radialGradient id="iB0hGSc" cx="0" cy="0" r="1" gradientTransform="matrix(.32643 1.12328 -2.01036 .58422 8.429 18.801)" gradientUnits="userSpaceOnUse"><stop offset=".458" class="z4bdcvbyn"/><stop offset="1" class="am74-ybbl"/></radialGradient><radialGradient id="io6TTRu" cx="0" cy="0" r="1" gradientTransform="matrix(-.64475 .91423 -.79094 -.5578 10.785 19.01)" gradientUnits="userSpaceOnUse"><stop class="thquhzfce"/><stop offset=".612" class="viko81uad"/></radialGradient><linearGradient id="i2gxm4b" x1="1.558" x2="4.433" y1="23.072" y2="23.072" gradientUnits="userSpaceOnUse"><stop class="een5o6ben"/><stop offset="1" class="q9o8yf9um"/></linearGradient><linearGradient id="ifBG60c" x1="16" x2="16" y1="30.947" y2="23.759" gradientUnits="userSpaceOnUse"><stop class="x6dparvak"/><stop offset="1" class="ml1-dp5ml"/></linearGradient><linearGradient id="iqE64Bb" x1="16" x2="16" y1="30.22" y2="29.267" gradientUnits="userSpaceOnUse"><stop class="vcy4zh8qa"/><stop offset=".648" class="e77v3pbme"/></linearGradient><linearGradient id="ixYv0rc" x1="9.557" x2="9.213" y1="14.067" y2="13.848" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="ib4nc9d" x1="4.277" x2="3.933" y1="14.067" y2="13.848" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iwpKZ9b" x1="15.87" x2="6.182" y1="21.58" y2="21.58" gradientUnits="userSpaceOnUse"><stop class="gejtoe1xf"/><stop offset="1" class="ocs0-rubn"/></linearGradient><linearGradient id="ieTRoac" x1="8.464" x2="7.214" y1="14.947" y2="16.197" gradientUnits="userSpaceOnUse"><stop class="y-906lr6h"/><stop offset="1" class="heu52db-b"/></linearGradient><linearGradient id="iughEVN" x1="5.589" x2="6.026" y1="14.65" y2="15.181" gradientUnits="userSpaceOnUse"><stop class="in1b14hsr"/><stop offset="1" class="xfot5fv0n"/></linearGradient><linearGradient id="iSKgSCc" x1="6.885" x2="6.431" y1="14.281" y2="13.992" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iIM8YLc" x1="6.057" x2="7.932" y1="20.947" y2="21.384" gradientUnits="userSpaceOnUse"><stop class="hzqqh9d3s"/><stop offset="1" class="zysosfb3g"/></linearGradient><linearGradient id="ilWlRVp" x1="18.043" x2="23.172" y1="19.17" y2="17.189" gradientUnits="userSpaceOnUse"><stop class="gk_vqxbvi"/><stop offset="1" class="qesieubvb"/></linearGradient><linearGradient id="iwLZ4DU" x1="22.9" x2="16.582" y1="7.092" y2="16.794" gradientUnits="userSpaceOnUse"><stop class="fiswy_but"/><stop offset="1" class="pzclwgb-d"/></linearGradient><filter id="iBxtAEM" width="9.46" height="10.412" x="15.435" y="12.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".4"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.231373 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4361"/></filter><filter id="iXUmtLb" width="11.773" height="11.773" x="1.129" y="8.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4361" stdDeviation="1.5"/></filter><filter id="iBGm97d" width="7.481" height="8.318" x="16.168" y="15.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4361" stdDeviation=".75"/></filter><filter id="iQVH2kb" width="8.801" height="18.947" x="20.977" y="4.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4361" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:otter" /></template>
<style>
.am74-ybbl {
  stop-color: var(--svg-color--63382e, #63382E);
  stop-opacity: 0;
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bjsaxbbek {
  d: path("M10.755 16.57h-.99c-.58 0-1.05.47-1.05 1.05v.99c0 .27.05.54.13.78c.23-.15.42-.36.52-.63a1.117 1.117 0 1 1 2.09.79c-.21.55-.55 1.03-.98 1.4c.22.06.45.1.68.1h.99c.58 0 1.05-.47 1.05-1.05v-.99c0-1.35-1.09-2.44-2.44-2.44");
}

.blzybplow {
  stop-color: var(--svg-color--5f3235, #5F3235);
  stop-opacity: 0;
}

.bw3h0_6sg {
  stop-color: var(--svg-color--cb5b5b, #CB5B5B);
  stop-opacity: 0;
}

.c-d-yqgeb {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  fill-rule: evenodd;
  d: path("M10.706 18.06c.598.17.944.794.773 1.391c-.083.29-.268.639-.505.955a3.55 3.55 0 0 1-1.111.983c-.693.382-1.413.453-1.98.442c-.396-.007-.836-.066-1.1-.101q-.121-.017-.184-.024a1.125 1.125 0 1 1 .23-2.238c.153.016.285.034.41.05c.225.031.425.059.688.063c.357.007.635-.044.849-.162a1.3 1.3 0 0 0 .398-.362a1.5 1.5 0 0 0 .147-.243a1.125 1.125 0 0 1 1.385-.754");
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.cotncwbxg {
  d: path("M23.275 12.158c-.62 0-1.12.496-1.12 1.112v1.112h-.79c-3.28 0-5.93 2.642-5.93 5.89v1.897h8.96V13.27c0-.616-.5-1.112-1.12-1.112");
}

.cwteddcxz {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M22.276 5.93c1.84.37 6.002 2.532 6.002 7.14v9.061");
}

.d47hqgble {
  stop-color: var(--svg-color--bfb8c1, #BFB8C1);
  stop-opacity: 0;
}

.dp37m6sqm {
  stop-color: var(--svg-color--815352, #815352);
  stop-opacity: 0;
}

.e77v3pbme {
  stop-color: var(--svg-color--925690, #925690);
  stop-opacity: 0;
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.een5o6ben {
  stop-color: var(--svg-color--684c49, #684C49);
}

.fiswy_but {
  stop-color: var(--svg-color--a27168, #A27168);
}

.foqbprdif {
  stop-color: var(--svg-color--83615c, #83615C);
}

.fr9uvvbni {
  stop-color: var(--svg-color--58302b, #58302B);
}

.ft5dv1b6b {
  fill: none;
}

.ftxg8rssm {
  d: path("m13.275 18.81l-1.68.17c-.03.01-.05.02-.08.02c.02.18.01.37-.06.55a3.55 3.55 0 0 1-3.3 2.28h-1.4c.72 2.15 2.74 3.7 5.14 3.7h4.67V22.5c0-2.1.95-3.32 1.29-3.69z");
}

.gejtoe1xf {
  stop-color: var(--svg-color--c77b4b, #C77B4B);
}

.gk_vqxbvi {
  stop-color: var(--svg-color--8b6159, #8B6159);
}

.h99mlrh7q {
  stop-color: var(--svg-color--75403b, #75403B);
}

.hd3dwm1lf {
  stop-color: var(--svg-color--6c2454, #6C2454);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.heu52db-b {
  stop-color: var(--svg-color--ffcd8f, #FFCD8F);
  stop-opacity: 0;
}

.hhq5fhbhd {
  d: path("M7.015 15.46a.66.66 0 1 0 0-1.32a.66.66 0 0 0 0 1.32");
}

.hy5cs1gce {
  cx: 3.124px;
  cy: 11.072px;
  r: 1.086px;
}

.hzqqh9d3s {
  stop-color: var(--svg-color--754442, #754442);
}

.i-kow0--d {
  stop-color: var(--svg-color--8a6861, #8A6861);
}

.in1b14hsr {
  stop-color: var(--svg-color--c69261, #C69261);
}

.inks3jb8f {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M20.715 5.01c5.14.18 9.26 4.19 9.26 9.32l.03 7.51c0 4.51-3.66 8.17-8.17 8.17h-11.67c-4.51 0-8.17-3.66-8.17-8.16v-6.96q0-.218.018-.43h.006a4.9 4.9 0 0 1 .845-2.4l-.002-.001c.357-.53.813-.988 1.341-1.348l.002.008c.81-.55 1.78-.87 2.83-.87s2.02.32 2.83.87l.003-.012c.53.36.987.82 1.345 1.35l-.008.002a5 5 0 0 1 .87 2.83v2.72c0 .66.54 1.2 1.2 1.2h4.58a5.9 5.9 0 0 1 4.64-2.24h.79v-1.12c0-.62.5-1.12 1.12-1.12s1.12.5 1.12 1.12v-1.28c0-3.69-2.12-6.48-5.18-8.08c-.54-.28-.33-1.1.28-1.08z");
}

.j5g4f5fzp {
  fill-rule: evenodd;
  d: path("M10.706 18.06c.598.17.944.794.773 1.391c-.083.29-.268.639-.505.955a3.55 3.55 0 0 1-1.111.983c-.693.382-1.413.453-1.98.442c-.396-.007-.836-.066-1.1-.101q-.121-.017-.184-.024a1.125 1.125 0 1 1 .23-2.238c.153.016.285.034.41.05c.225.031.425.059.688.063c.357.007.635-.044.849-.162a1.3 1.3 0 0 0 .398-.362a1.5 1.5 0 0 0 .147-.243a1.125 1.125 0 0 1 1.385-.754");
}

.jsxd41bok {
  stop-color: var(--svg-color--ceb5e1, #CEB5E1);
}

.k6t69jqpd {
  stop-color: var(--svg-color--bfb8c1, #BFB8C1);
}

.kilc9osws {
  fill: var(--svg-color--d19666, #D19666);
  d: path("m8.585 15.05l-.79-.79c-.22-.22-.51-.33-.8-.33s-.58.11-.8.33l-.79.79a1.11 1.11 0 0 0 0 1.58c.44.44 1.14.44 1.58 0l.01-.01l.01.01c.44.44 1.14.44 1.58 0c.43-.44.43-1.14 0-1.58");
}

.lcjgqb7wo {
  stop-color: var(--svg-color--714a41, #714A41);
}

.mcwwoxy4j {
  cx: 7.015px;
  cy: 14.139px;
  r: 2.886px;
  fill: var(--svg-color--d2a06e, #D2A06E);
}

.ml1-dp5ml {
  stop-color: var(--svg-color--75386c, #75386C);
  stop-opacity: 0;
}

.n6iszy2th {
  stop-color: var(--svg-color--7b5c55, #7B5C55);
}

.npqnkx3xy {
  stop-color: var(--svg-color--ceb5e1, #CEB5E1);
  stop-opacity: 0;
}

.nqx299b1l {
  cx: 10.906px;
  cy: 11.072px;
  r: 1.086px;
}

.o9_ekcbfi {
  d: path("M20.715 5.01c5.14.18 9.26 4.19 9.26 9.32l.03 7.51c0 4.51-3.66 8.17-8.17 8.17h-11.67c-4.51 0-8.17-3.66-8.17-8.16v-6.96q0-.218.018-.43h.006a4.9 4.9 0 0 1 .845-2.4l-.002-.001c.357-.53.813-.988 1.341-1.348l.002.008c.81-.55 1.78-.87 2.83-.87s2.02.32 2.83.87l.003-.012c.53.36.987.82 1.345 1.35l-.008.002a5 5 0 0 1 .87 2.83v2.72c0 .66.54 1.2 1.2 1.2h4.58a5.9 5.9 0 0 1 4.64-2.24h.79v-1.12c0-.62.5-1.12 1.12-1.12s1.12.5 1.12 1.12v-1.28c0-3.69-2.12-6.48-5.18-8.08c-.54-.28-.33-1.1.28-1.08z");
}

.ocs0-rubn {
  stop-color: var(--svg-color--c77b4b, #C77B4B);
  stop-opacity: 0;
}

.oj7susspq {
  stop-color: var(--svg-color--83615c, #83615C);
  stop-opacity: 0;
}

.owego8bwu {
  stop-color: var(--svg-color--cb5b5b, #CB5B5B);
}

.oy2694bda {
  stop-color: var(--svg-color--6f534d, #6F534D);
  stop-opacity: 0;
}

.pa1kjdjbv {
  stop-color: var(--svg-color--714a41, #714A41);
  stop-opacity: 0;
}

.pd0fkd17h {
  stop-color: var(--svg-color--815352, #815352);
}

.pv7vaoa5k {
  fill: var(--svg-color--78544d, #78544D);
  d: path("M23.275 12.158c-.62 0-1.12.496-1.12 1.112v1.112h-.79c-3.28 0-5.93 2.642-5.93 5.89v1.897h8.96V13.27c0-.616-.5-1.112-1.12-1.112");
}

.pyvm_yb8a {
  stop-color: var(--svg-color--9a746e, #9A746E);
  stop-opacity: 0;
}

.pzclwgb-d {
  stop-color: var(--svg-color--a17168, #A17168);
  stop-opacity: 0;
}

.q9o8yf9um {
  stop-color: var(--svg-color--684c49, #684C49);
  stop-opacity: 0;
}

.qesieubvb {
  stop-color: var(--svg-color--8b6159, #8B6159);
  stop-opacity: 0;
}

.r2nehz-yy {
  stop-color: var(--svg-color--5f3235, #5F3235);
}

.rvbm7mbnx {
  d: path("M9.655 14.96a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.thquhzfce {
  stop-color: var(--svg-color--926d67, #926D67);
}

.tpcciqdof {
  d: path("m8.585 15.05l-.79-.79c-.22-.22-.51-.33-.8-.33s-.58.11-.8.33l-.79.79a1.11 1.11 0 0 0 0 1.58c.44.44 1.14.44 1.58 0l.01-.01l.01.01c.44.44 1.14.44 1.58 0c.43-.44.43-1.14 0-1.58");
}

.tsq6q82xq {
  stop-color: var(--svg-color--804135, #804135);
}

.u57yu_b2x {
  stop-color: var(--svg-color--612d22, #612D22);
  stop-opacity: 0;
}

.uvq-lrb2i {
  d: path("M12.955 19.31a1.36 1.36 0 1 0 0-2.72a1.36 1.36 0 0 0 0 2.72");
}

.vcy4zh8qa {
  stop-color: var(--svg-color--925690, #925690);
}

.viko81uad {
  stop-color: var(--svg-color--926d67, #926D67);
  stop-opacity: 0;
}

.vmh73wzcg {
  d: path("M4.375 14.96a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.w7csafb9y {
  fill: var(--svg-color--754442, #754442);
  fill-rule: evenodd;
  d: path("M10.706 18.06c.598.17.944.794.773 1.391c-.083.29-.268.639-.505.955a3.55 3.55 0 0 1-1.111.983c-.693.382-1.413.453-1.98.442c-.396-.007-.836-.066-1.1-.101q-.121-.017-.184-.024a1.125 1.125 0 1 1 .23-2.238c.153.016.285.034.41.05c.225.031.425.059.688.063c.357.007.635-.044.849-.162a1.3 1.3 0 0 0 .398-.362a1.5 1.5 0 0 0 .147-.243a1.125 1.125 0 0 1 1.385-.754");
}

.wnt7mdb7l {
  stop-color: var(--svg-color--863169, #863169);
  stop-opacity: 0;
}

.x2hd0sbwb {
  stop-color: var(--svg-color--612d22, #612D22);
}

.x6dparvak {
  stop-color: var(--svg-color--75386c, #75386C);
}

.xfot5fv0n {
  stop-color: var(--svg-color--c69261, #C69261);
  stop-opacity: 0;
}

.xvvr0ibxu {
  stop-color: var(--svg-color--9a746e, #9A746E);
}

.y-906lr6h {
  stop-color: var(--svg-color--ffcd8f, #FFCD8F);
}

.y7aejbcai {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M22.088 17.74c-1.316.216-4.045 1.244-4.045 4.947");
}

.z4bdcvbyn {
  stop-color: var(--svg-color--63382e, #63382E);
}

.z4s2w9nul {
  fill: var(--svg-color--f1edf3, #F1EDF3);
  d: path("M10.755 16.57h-.99c-.58 0-1.05.47-1.05 1.05v.99c0 .27.05.54.13.78c.23-.15.42-.36.52-.63a1.117 1.117 0 1 1 2.09.79c-.21.55-.55 1.03-.98 1.4c.22.06.45.1.68.1h.99c.58 0 1.05-.47 1.05-1.05v-.99c0-1.35-1.09-2.44-2.44-2.44");
}

.zex8bmbii {
  stop-color: var(--svg-color--804135, #804135);
  stop-opacity: 0;
}

.zgj8xvbdy {
  fill: var(--svg-color--754442, #754442);
  d: path("M20.715 5.01c5.14.18 9.26 4.19 9.26 9.32l.03 7.51c0 4.51-3.66 8.17-8.17 8.17h-11.67c-4.51 0-8.17-3.66-8.17-8.16v-6.96q0-.218.018-.43h.006a4.9 4.9 0 0 1 .845-2.4l-.002-.001c.357-.53.813-.988 1.341-1.348l.002.008c.81-.55 1.78-.87 2.83-.87s2.02.32 2.83.87l.003-.012c.53.36.987.82 1.345 1.35l-.008.002a5 5 0 0 1 .87 2.83v2.72c0 .66.54 1.2 1.2 1.2h4.58a5.9 5.9 0 0 1 4.64-2.24h.79v-1.12c0-.62.5-1.12 1.12-1.12s1.12.5 1.12 1.12v-1.28c0-3.69-2.12-6.48-5.18-8.08c-.54-.28-.33-1.1.28-1.08z");
}

.zimrksbbk {
  stop-color: var(--svg-color--58302b, #58302B);
  stop-opacity: 0;
}

.zpyhqtffa {
  stop-color: var(--svg-color--c18954, #C18954);
}

.zysosfb3g {
  stop-color: var(--svg-color--754442, #754442);
  stop-opacity: 0;
}

</style>
