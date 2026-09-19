<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvv2kfblg"/><path class="y0yr8_kdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-approval" /></template>
<style>
.pvv2kfblg {
  fill: currentColor;
  d: path("M6 16h12v2H6zm6-12c-1.66 0-3 1.34-3 3l3 4l3-4c0-1.66-1.34-3-3-3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.y0yr8_kdv {
  fill: currentColor;
  d: path("M12 2C9.24 2 7 4.24 7 7l5 7l5-7c0-2.76-2.24-5-5-5m0 9L9 7c0-1.66 1.34-3 3-3s3 1.34 3 3zm6 3H6c-1.1 0-2 .9-2 2v6h16v-6c0-1.1-.9-2-2-2m0 4H6v-2h12z");
}

</style>
