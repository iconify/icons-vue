<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qhobf5bpp"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shokoladnitsa" /></template>
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

.qhobf5bpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.276 15.575c1.402 2.979 1.02 6.078.386 8.451s-2.022 5.16-1.437 8.402m-6.107-16.856c1.402 2.986 1.02 6.081.385 8.455s-2.022 5.159-1.436 8.401m-6.108-16.856c1.402 2.986 1.02 6.081.386 8.455s-2.022 5.159-1.437 8.401");
}

</style>
