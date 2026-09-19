<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="id601r10a"/><circle class="n7pmbrbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sugarizer" /></template>
<style>
.id601r10a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.642 31.265l6.631-6.631a3.282 3.282 0 0 0-4.642-4.642L24 26.623l-6.631-6.631a3.282 3.282 0 1 0-4.642 4.642l6.631 6.631l-6.631 6.632a3.282 3.282 0 1 0 4.642 4.642L24 35.907l6.631 6.632a3.282 3.282 0 0 0 4.642-4.642Z");
}

.n7pmbrbkp {
  cx: 23.999px;
  cy: 10.774px;
  r: 6.274px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
