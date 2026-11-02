<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eqqa79byp"/><path class="kfz_v3cnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-duotone-sharp" /></template>
<style>
.eqqa79byp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 6c0-.265.105-.52.293-.707l3-3A1 1 0 0 1 8 2h8c.265 0 .52.105.707.293l3 3A1 1 0 0 1 20 6v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

.ft5dv1b6b {
  fill: none;
}

.kfz_v3cnd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 17V6l3-3h8l3 3v11zm3 0l-2 4m10-4l2 4M5 10h14M9 14h.01M15 14h.01");
}

</style>
