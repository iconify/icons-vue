<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tut7yda2e"/><path class="h7bf-rbgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h7bf-rbgv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 3l6 3l2-1c1.838-.919 4 .162 4 2v9c0 1.226-.774 2.387-2 3l-4 2l-6-3l-2 1c-1.838.919-4-.162-4-2V8c0-1.226.774-2.387 2-3zm0 0v15m6-12v15");
}

.tut7yda2e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 18a1 1 0 0 1-.553.894l-2 1c-1.12.56-2.457.597-3.583.034a3.44 3.44 0 0 1-1.328-1.154A3.2 3.2 0 0 1 2 17V8c0-1.693 1.069-3.152 2.553-3.894l4-2A1 1 0 0 1 10 3Zm6.553-13.894c1.12-.56 2.457-.597 3.583-.034c.534.267.996.658 1.328 1.154C21.816 5.753 22 6.367 22 7v9c0 1.693-1.069 3.152-2.553 3.894l-4 2A1 1 0 0 1 14 21V6c0-.379.214-.725.553-.894Z");
}

</style>
