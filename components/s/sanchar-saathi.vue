<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ouuz29qhn"/><circle class="qdlcaib-q"/><path class="s9htstgsw"/><circle class="ee1qzbc-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sanchar-saathi" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ee1qzbc-x {
  cx: 27.847px;
  cy: 22.109px;
  r: 1.116px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ouuz29qhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.913 14.57h2.204v3.847h-2.204zm-1.285 1.156c-.216.468-.238.993 0 1.535m4.744-1.535c.216.468.238.993 0 1.535m-5.862-2.275c-.648.834-.689 2.105 0 3.015m6.98-3.015c.648.834.689 2.105 0 3.015m-4.378 2.153c.732 3.846.381 12.731-16.211 16.88c10.557-4.895 11.554-12.882-1.265-24.22c8.853 3.68 13.704 12.892 13.704 12.892c2.118-.533 3.604-2.145 3.772-5.552");
}

.qdlcaib-q {
  cx: 20.153px;
  cy: 22.109px;
  r: 1.116px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s9htstgsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.888 20.154c-.732 3.846-.381 12.731 16.211 16.88c-10.557-4.895-11.554-12.882 1.265-24.22c-8.853 3.68-13.704 12.892-13.704 12.892c-2.118-.533-3.604-2.145-3.772-5.552");
}

</style>
