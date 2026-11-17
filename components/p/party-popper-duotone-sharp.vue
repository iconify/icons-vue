<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rziax7bgo"/><path class="ykc-7hbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:party-popper-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rziax7bgo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m7 9l-.316.948C6.667 9.602 6.75 9.251 7 9M3 21L6.684 9.948c.129 2.447 4.921 7.239 7.368 7.368L15 17c-.251.25-.602.333-.948.316Z");
}

.ykc-7hbck {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 9L3 21l12-4c-2 2-10-6-8-8m0 0c2-2 10 6 8 8S5 11 7 9m4-6v2m5 3l2-2m1 7h2M15 3h.01M21 9h-.01");
}

</style>
