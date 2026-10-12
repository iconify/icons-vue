<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="prlmlobug"/><circle class="m11btbbwe"/><path class="buajp_9_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spanner-ring" /></template>
<style>
.buajp_9_f {
  d: path("m8.49 18.1l-.64.64q-.21.21-.5.13l-.87-.23q-.29-.08-.37-.37l-.23-.87q-.08-.29.13-.5l.64-.64q.21-.21.5-.13l.87.23q.29.08.37.37l.23.87q.08.29-.13.5m9.52-13.83a3.5 3.5 0 1 1-1.88-1.32l-2.08 2.94l1.88 1.33Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m11btbbwe {
  cx: 7.25px;
  cy: 17.5px;
  r: 3.75px;
}

.prlmlobug {
  d: path("m10.25 15.25l3.94-5.57l-1.88-1.33l-3.94 5.57Z");
}

</style>
