<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0avdm_se"/><path class="qpeg5hafp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-today" /></template>
<style>
.qpeg5hafp {
  fill: currentColor;
  d: path("M5 5h14v2H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.x0avdm_se {
  fill: currentColor;
  d: path("M19 3h-1V1h-2v2H8V1H6v2H5c-1.11 0-1.99.9-1.99 2L3 19a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V9h14zm0-12H5V5h14zm-7 4H7v5h5z");
}

</style>
