<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="hgthhfh5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-lock-28-regular" /></template>
<style>
.hgthhfh5w {
  fill: currentColor;
  d: path("M20 14a3 3 0 0 1 3 3v1h.5a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2h.5v-1a3 3 0 0 1 3-3m0 7a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-5.25-6c.581 0 1.11.222 1.509.584A4 4 0 0 0 16 17v.041q-.261.045-.505.13a.75.75 0 0 0-.745-.671H4.25a.75.75 0 0 0-.75.75v.495l.001.018q.001.03.008.1c.01.094.03.235.074.409c.087.347.261.812.61 1.278c.673.897 2.115 1.95 5.307 1.95c1.868 0 3.134-.363 4-.842v1.658c-1.026.418-2.334.684-4 .684c-3.558 0-5.491-1.197-6.506-2.55a5.1 5.1 0 0 1-.866-1.815a4.5 4.5 0 0 1-.125-.797L2 17.78v-.531A2.25 2.25 0 0 1 4.25 15zm5.25.5a1.5 1.5 0 0 0-1.5 1.5v1h3v-1a1.5 1.5 0 0 0-1.5-1.5M9.5 4a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M20 6a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7M9.5 5.5a3 3 0 1 0 0 6a3 3 0 0 0 0-6m10.5 2a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>
