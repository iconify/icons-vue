<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zd8xgr6nc"/><path class="prtaznesx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sound-effect-sharp" /></template>
<style>
.prtaznesx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 18h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zd8xgr6nc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 6v-.9h2.22l2.64-2.22l.942-.843L13.01 3.3v8.4l.042 1.263l-.942-.843L9.47 9.9H7.25V9ZM16 5.5l1.789 2L16 9.5m-9.5 5.25h11v6.5h-11z");
}

</style>
