<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o707_xbjc"/><path class="h69nhiyzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:prevo" /></template>
<style>
.h69nhiyzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.21 26.83a3.43 3.43 0 0 1-3 1.74a3.45 3.45 0 0 1-3.45-3.45v-2.24a3.45 3.45 0 0 1 3.45-3.45a3.45 3.45 0 0 1 3.44 3.45V24h-6.88m-3.67 2.83a3.43 3.43 0 0 1-3 1.74a3.46 3.46 0 0 1-3.45-3.45v-2.24a3.46 3.46 0 0 1 3.45-3.45a3.46 3.46 0 0 1 3 1.73m-4.77-4.66l1.55-.87l1.55.87");
}

.o707_xbjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.5v35a2 2 0 0 0 2 2h2.33v-39H10.4a2 2 0 0 0-2 2m4.33-2v39H37.6a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2Z");
}

</style>
