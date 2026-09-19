<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q8kqfbk9w"/><path class="h0n3ghd1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nz-tides" /></template>
<style>
.h0n3ghd1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.985 22.204C10.566 3.403 22.205 3.403 25.795 24c1.787 13.434 12.542 13.434 15.22-1.796M15.934 8.77v26.878m17.026 0v-1.796");
}

.q8kqfbk9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.871 0 21.5 9.629 21.5 21.5S35.871 45.5 24 45.5S2.5 35.871 2.5 24S12.129 2.5 24 2.5");
}

</style>
