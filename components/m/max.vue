<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dyk37zaky"/><path class="yq0wb8buq"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:max" /></template>
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

.dyk37zaky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.5 19.619l-6.6 8.762m6.6 0l-6.6-8.762M7.5 28.381v-5.234c0-1.821 1.48-3.3 3.3-3.3s3.3 1.479 3.3 3.3v5.234");
}

.yq0wb8buq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.1 23.147c0-1.821 1.48-3.3 3.3-3.3s3.3 1.479 3.3 3.3v5.234m9.786-3.3c0 1.82-1.48 3.3-3.3 3.3s-3.3-1.48-3.3-3.3v-2.162c0-1.82 1.48-3.3 3.3-3.3s3.3 1.48 3.3 3.3m0 5.462v-8.762M27.186 25v-2");
}

</style>
