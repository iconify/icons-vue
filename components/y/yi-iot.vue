<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="mlt3fdcml"/><circle class="gmkp1rwwx"/><path class="we9uzn61x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yi-iot" /></template>
<style>
.gmkp1rwwx {
  cx: 26.524px;
  cy: 16.436px;
  r: 3.366px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mlt3fdcml {
  cx: 25.157px;
  cy: 16.716px;
  r: 11.219px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.we9uzn61x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.65 24.03c-1.011.044-10.067 1.405-10.036 9.997c.02 5.409 3.77 8.473 8.587 8.389l18.1.084c3.635-.084 7.94-2.21 8.081-7.126c.128-4.417-2.806-8.66-10.849-8.813");
}

</style>
