<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="gzyv120hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:new-launcher" /></template>
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

.gzyv120hd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.5 28.459l1.93-8.884l4.011 8.884l1.93-8.884m21.129 0l-2.835 8.884l-2.834-8.884l-2.835 8.884l-1.974-6.19c-.603-1.89-2.468-3.166-4.43-2.867l-.071.012c-1.985.332-3.567 2.004-3.808 4.001a4.65 4.65 0 0 0 4.612 5.226m-4.647-4.647h5.581");
}

</style>
