<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="v4i2ew1ke"/><path class="se8mzsbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-photo-camera" /></template>
<style>
.se8mzsbii {
  fill: currentColor;
  d: path("M9 2L7.17 4H2v16h20V4h-5.17L15 2zm3 15c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.24 5-5 5");
}

.v4i2ew1ke {
  cx: 12px;
  cy: 12px;
  r: 3px;
  fill: currentColor;
}

</style>
