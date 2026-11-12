<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0rb-ib5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-off-fill-round" /></template>
<style>
.b0rb-ib5c {
  fill: currentColor;
  d: path("m5.707 1.293l17 17a1 1 0 0 1-.873 1.693A3 3 0 0 1 19 22h-2a3 3 0 0 1-3-3v-1a3 3 0 0 1 2.611-2.975l-1.953-1.953A3 3 0 0 0 14 13h-4a3.01 3.01 0 0 0-2.831 2.005A3 3 0 0 1 10 18v1a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-1a3 3 0 0 1 3-3h.099A5.01 5.01 0 0 1 10 11h2.586l-2.033-2.033a3.01 3.01 0 0 1-2.52-2.52l-3.74-3.74a.999.999 0 1 1 1.414-1.414M9.593 2.35C10.026 2.12 10.51 2 11 2h2a3 3 0 0 1 3 3v1a3 3 0 0 1-.761 1.997Z");
}

</style>
