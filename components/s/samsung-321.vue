<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="vz2riqb8u"/><path class="smomc7b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-321" /></template>
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

.smomc7b-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.014 18.586c.9-.75 1.869-1.092 4.045-1.086l.506.003a3.25 3.25 0 1 1 0 6.498m-2.498.001h2.497");
}

.vz2riqb8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.736 19.27l3.25-1.77v13m-14.775-8.694a4.31 4.31 0 0 1 5.161-4.224c1.806.347 3.248 1.91 3.428 3.74c.134 1.36-.297 2.704-1.237 3.53C27.82 26.38 22.21 30.5 22.21 30.5h8.613m-19.808-1.096c.897.752 1.866 1.096 4.042 1.096h.507a3.25 3.25 0 1 0 0-6.498");
}

</style>
