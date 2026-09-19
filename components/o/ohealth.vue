<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jdyg2zbjw"/><path class="bn7dz-b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ohealth" /></template>
<style>
.bn7dz-b9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.9 39.149c1.145 1.145 3.13 1.142 4.272 0");
}

.jdyg2zbjw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.356 24.638c-3.808-3.808-3.808-9.98 0-13.789c3.807-3.807 9.98-3.807 13.788 0m5.712.001c3.808-3.808 9.98-3.808 13.788 0s3.808 9.98 0 13.788m-33.288 0L21.9 39.15m18.744-14.512L26.172 39.15m-5.028-28.3l2.858 2.854m2.854-2.854l-2.854 2.854m.02.016c6.995 6.995 7.644 18.12 1.51 25.88");
}

</style>
