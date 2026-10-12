<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><circle class="d8mt2_n-r"/><path class="ank1sub4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:notary-stamp" /></template>
<style>
.ank1sub4o {
  d: path("m12.14 8.92l.75 1.69q.14.32.49.35l1.84.19q.35.04.09.28l-1.38 1.23q-.26.23-.18.58l.38 1.8q.07.34-.23.17l-1.6-.92q-.3-.18-.6 0l-1.6.92q-.3.17-.23-.17l.38-1.8q.08-.35-.18-.58l-1.38-1.23q-.26-.24.09-.28l1.84-.19q.35-.03.49-.35l.75-1.69q.14-.32.28 0");
}

.d8mt2_n-r {
  cx: 12px;
  cy: 12px;
  r: 6.25px;
}

.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
