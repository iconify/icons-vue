<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sj61xtb-l"/><path class="hmy1l9b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sharex" /></template>
<style>
.hmy1l9b1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.657 17.122v-5.35a3.64 3.64 0 0 1 2.867-3.558l15.982-3.478a2 2 0 0 1 2.426 1.954v15.737a3.64 3.64 0 0 1-2.868 3.558l-18.407 4.006l6.107 3.294v-4.623");
}

.sj61xtb-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.343 30.878v5.35a3.64 3.64 0 0 1-2.867 3.558l-15.982 3.478a2 2 0 0 1-2.426-1.954V25.573a3.64 3.64 0 0 1 2.868-3.558l18.407-4.006l-6.107-3.294v4.623");
}

</style>
