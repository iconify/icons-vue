<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="jbtc8_bym"/><path class="gjk5a5bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quantum" /></template>
<style>
.gjk5a5bjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.815 43.5c-7.273-4.534-11.003-8.17-12.94-10.909M21.921 4.614v37.46");
}

.jbtc8_bym {
  cx: 24px;
  cy: 23.344px;
  r: 18.844px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
