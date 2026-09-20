<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qc8-njbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:speaker-low-light" /></template>
<style>
.qc8-njbnr {
  fill: currentColor;
  d: path("M154.64 26.61a6 6 0 0 0-6.32.65L77.94 82H32a14 14 0 0 0-14 14v64a14 14 0 0 0 14 14h45.94l70.38 54.74A6 6 0 0 0 158 224V32a6 6 0 0 0-3.36-5.39M30 160V96a2 2 0 0 1 2-2h42v68H32a2 2 0 0 1-2-2m116 51.73l-60-46.66V90.93l60-46.66ZM206 128a37.94 37.94 0 0 1-9.5 25.14a6 6 0 1 1-9-7.94a26 26 0 0 0 0-34.37a6 6 0 0 1 9-7.93A38 38 0 0 1 206 128");
}

</style>
