<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cm6tpt3au"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:muchbetter" /></template>
<style>
.cm6tpt3au {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.444 34.94l-6.667-22.857m4.56-1.33l6.75-1.968a7.14 7.14 0 0 1 3.998 13.708a7.14 7.14 0 1 1 3.998 13.709L19.773 39.5m7.312-17.007l-6.75 1.971");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
