<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="flqze5xiy"/><circle class="xlypk7brp"/><path class="av72kwbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mindicator" /></template>
<style>
.av72kwbky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.532 24h9.78m-3.792-2.19L37.312 24l-3.792 2.19M20.468 24h-9.78m3.792 2.19L10.688 24l3.792-2.19");
}

.flqze5xiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 18.54h39v11.048h-39Zm28.302 11.071a10.438 10.438 0 0 1-17.603 0m-.091-11.077a10.438 10.438 0 0 1 17.784 0m6.386 11.064a16.273 16.273 0 0 1-30.559 0m-.045-11.07a16.273 16.273 0 0 1 30.653.01");
}

.xlypk7brp {
  cx: 24px;
  cy: 24px;
  r: 1.867px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
