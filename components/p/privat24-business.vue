<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eqt0vm0yn"/><path class="tv7tv0blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:privat24-business" /></template>
<style>
.eqt0vm0yn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 9.5v10.8h8.325v-5.55H33.25v19.425h-3.7V42.5h8.95a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4");
}

.tv7tv0blv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.05 29.55H7.5c-1.1 0-2 .9-2 2v8.95c0 1.1.9 2 2 2H22c1.1 0 2-.9 2-2v-8.95c0-1.1-.9-2-2-2h-3.55v-3.7h-7.4zm7.4 0h-7.4");
}

</style>
