<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uvixfrc4b"/><path class="s3i65fbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:whatsapp-downloader" /></template>
<style>
.s3i65fbrt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.704 25.204L24 34.5l9.296-9.296M24 34.5v-21");
}

.uvixfrc4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.502c-11.884.013-21.508 9.657-21.495 21.541A21.5 21.5 0 0 0 5.152 34.36l-1.65 10.139l10.139-1.65c10.41 5.71 23.477 1.901 29.188-8.509s1.9-23.477-8.509-29.187A21.5 21.5 0 0 0 24 2.502");
}

</style>
