<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x-ihj8qmb"/><path class="evhhslgiz"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-reminder" /></template>
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

.evhhslgiz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.377 14.574L20.333 26.577a.594.594 0 0 1-.836-.077l-4.861-5.842M9.5 24.944l5.135-4.286m.711 10.111l5.135-4.286m13.896-11.909l4.123 4.663");
}

.x-ihj8qmb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 19.237L23.086 32.064a5.89 5.89 0 0 1-8.294-.76L9.5 24.944");
}

</style>
