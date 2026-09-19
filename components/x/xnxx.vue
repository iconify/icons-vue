<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w-gbw5bmb"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xnxx" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.w-gbw5bmb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.503 19.648l5.321 8.704m0-8.704l-5.321 8.704m7.893 0v-8.704l5.321 8.704v-8.704m2.571 0l5.322 8.704m0-8.704l-5.322 8.704m7.894-8.704l5.321 8.704m0-8.704l-5.321 8.704");
}

</style>
