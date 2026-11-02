<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g64uz_bux"/><path class="s5jckyb7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subway-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g64uz_bux {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 12v7a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-7a6 6 0 1 1 12 0");
}

.s5jckyb7f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 12a5 5 0 0 1 10 0v7H7zm3 7l-1 2m5-2l1 2m-8-9h10M3 21v-9a9 9 0 0 1 18 0v9m-11-6h.01M14 15h.01");
}

</style>
