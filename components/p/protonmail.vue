<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eduji0u1u"/><path class="bzbpbbi0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:protonmail" /></template>
<style>
.bzbpbbi0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 27L22 35.38a4 4 0 0 0 4.26 0L39.5 27M24 10.74za9.43 9.43 0 0 1 9.43 9.43v1.73H14.57v-1.73A9.43 9.43 0 0 1 24 10.74");
}

.eduji0u1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5zA15.5 15.5 0 0 1 39.5 20v21.5a2 2 0 0 1-2 2h-27a2 2 0 0 1-2-2V20A15.5 15.5 0 0 1 24 4.5");
}

</style>
