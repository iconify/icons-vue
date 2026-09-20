<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h-6-qlj5w"/><path class="syr9tobza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pdfviewerplus" /></template>
<style>
.h-6-qlj5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.6 5.5a3.72 3.72 0 0 0-3.7 3.7v22.2a3.72 3.72 0 0 0 3.7 3.7h22.2a3.72 3.72 0 0 0 3.7-3.7V9.2a3.72 3.72 0 0 0-3.7-3.7Zm-3.7 7.4H9.5a4 4 0 0 0-4 4v21.9a3.72 3.72 0 0 0 3.7 3.7h21.9a4 4 0 0 0 4-4v-3.4m-.55-19.95h5.18m-5.18 5.17h3.38m-3.38-5.17v10.34");
}

.syr9tobza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.67 25.47V15.13h3.48a3.47 3.47 0 1 1 0 6.94h-3.48m9.44 3.42V15.11h1.76a5.19 5.19 0 0 1 5.19 5.19a5.19 5.19 0 0 1-5.19 5.19Z");
}

</style>
