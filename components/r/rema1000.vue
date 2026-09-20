<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ws9z-7b_x"/><path class="w52eerbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rema1000" /></template>
<style>
.w52eerbjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.076 4.5A3.64 3.64 0 0 0 9.43 8.133v31.734a3.64 3.64 0 0 0 3.645 3.633a3.64 3.64 0 0 0 3.644-3.633v-6.681h6.37l9.255 9.247a3.639 3.639 0 0 0 5.16-5.132l-6.154-6.15a14.27 14.27 0 0 0 7.219-12.307A14.606 14.606 0 0 0 23.794 4.5Zm3.644 7.266h7.073a7.088 7.088 0 1 1 0 14.154H16.72Z");
}

.ws9z-7b_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.076 39.866V8.133h10.718a10.88 10.88 0 0 1 11.13 10.71a10.88 10.88 0 0 1-11.13 10.71H13.076m11.502-.026l10.346 10.339");
}

</style>
