<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lppgr3bkl"/><path class="fcn74xbvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tabs-vertical" /></template>
<style>
.fcn74xbvm {
  d: path("M4.25 11.25h.5A1.75 1.75 0 0 1 6.5 13a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 2.5 13a1.75 1.75 0 0 1 1.75-1.75m0 6.25h.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 4.75 21h-.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lppgr3bkl {
  d: path("M4.5 2.5h15a2 2 0 0 1 2 2V19a2 2 0 0 1-2 2h-8.25a2 2 0 0 1-2-2V8.5H4.5a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2");
}

</style>
