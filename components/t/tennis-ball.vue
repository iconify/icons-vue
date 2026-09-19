<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="r9f6-eb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tennis-ball" /></template>
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

.r9f6-eb6f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.596 25.959a21.42 21.42 0 0 0 17.161-6.202A21.42 21.42 0 0 0 25.96 2.596m-3.919 42.808a21.42 21.42 0 0 1 6.202-17.161a21.42 21.42 0 0 1 17.161-6.202");
}

</style>
