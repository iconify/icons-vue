<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="t_2lkqbxb"><g mask="url(#SVGsZ1vtcCp)"><path class="b_xo1xq1b"/></g><path class="znwrltusi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:settings-star" /></template>
<style>
.b_xo1xq1b {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.36 4.57l.1-.96q.07-.74.82-.74h1.44q.75 0 .82.74l.1.96q.07.74.76 1.03l.43.18q.69.29 1.27-.19l.74-.61q.58-.48 1.11.05l1.02 1.02q.53.53.05 1.11l-.61.74q-.48.58-.19 1.27l.18.43q.29.69 1.03.76l.96.1q.74.07.74.82v1.44q0 .75-.74.82l-.96.1q-.74.07-1.03.76l-.18.43q-.29.69.19 1.27l.61.74q.48.58-.05 1.11l-1.02 1.02q-.53.53-1.11.05l-.74-.61q-.58-.48-1.27-.19l-.43.18q-.69.29-.76 1.03l-.1.96q-.07.74-.82.74h-1.44q-.75 0-.82-.74l-.1-.96q-.07-.74-.76-1.03l-.43-.18q-.69-.29-1.27.19l-.74.61q-.58.48-1.11-.05l-1.02-1.02q-.53-.53-.05-1.11l.61-.74q.48-.58.19-1.27l-.18-.43q-.29-.69-1.03-.76l-.96-.1q-.74-.07-.74-.82v-1.44q0-.75.74-.82l.96-.1q.74-.07 1.03-.76l.18-.43q.29-.69-.19-1.27l-.61-.74q-.48-.58.05-1.11l1.02-1.02q.53-.53 1.11-.05l.74.61q.58.48 1.27.19l.43-.18q.69-.29.76-1.03");
}

.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t_2lkqbxb {
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.znwrltusi {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.54 13.92l.83 1.82q.15.32.49.36l2 .22q.34.04.09.28l-1.48 1.35q-.26.24-.19.58l.4 1.96q.07.35-.23.17l-1.75-.99q-.3-.17-.6 0l-1.75.99q-.3.18-.23-.17l.4-1.96q.07-.34-.19-.58l-1.48-1.35q-.25-.24.09-.28l2-.22q.34-.04.49-.36l.83-1.82q.14-.32.28 0");
}

</style>
