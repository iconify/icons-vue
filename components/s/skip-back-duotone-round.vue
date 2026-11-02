<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="chal5ccye"/><path class="v-ql4db7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-back-duotone-round" /></template>
<style>
.chal5ccye {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m9.336 9.504l6-4A3 3 0 0 1 20 8v8a3 3 0 0 1-4.664 2.496l-6-4a2.998 2.998 0 0 1 0-4.992");
}

.ft5dv1b6b {
  fill: none;
}

.v-ql4db7v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15.336 5.504l-6 4c-1.781 1.187-1.781 3.805 0 4.992l6 4C17.33 19.826 20 18.396 20 16V8c0-2.396-2.67-3.825-4.664-2.496M4 5v14");
}

</style>
