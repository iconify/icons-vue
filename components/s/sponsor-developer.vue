<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gfayx_17q"/><path class="npertkbvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sponsor-developer" /></template>
<style>
.gfayx_17q {
  d: path("M12 20.5c-6-4-9.5-7.5-9.5-12c0-3 2.25-5 4.75-5c2 0 3.75 1.25 4.75 3c1-1.75 2.75-3 4.75-3c2.5 0 4.75 2 4.75 5c0 4.5-3.5 8-9.5 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.npertkbvz {
  d: path("M10 10.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M8 17.5c1.25-1.5 2.5-2 4-2s2.75.5 4 2");
}

</style>
