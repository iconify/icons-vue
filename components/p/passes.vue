<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rqnr2tkqr"/><path class="vc80y3b8t"/><path class="cstj53m1e"/><path class="ueusqblia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:passes" /></template>
<style>
.cstj53m1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.512 41.574h3.632a2.724 2.724 0 0 0 2.724-2.723V9.149a2.724 2.724 0 0 0-2.724-2.723h-3.632");
}

.rqnr2tkqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.726 23.988a4.83 4.83 0 0 1 2.57-4.27a4.34 4.34 0 0 0 2.26-3.85V8.224A2.724 2.724 0 0 0 25.833 5.5H8.223A2.724 2.724 0 0 0 5.5 8.223v31.553A2.724 2.724 0 0 0 8.223 42.5h17.61a2.724 2.724 0 0 0 2.723-2.723v-7.669a4.34 4.34 0 0 0-2.26-3.85a4.83 4.83 0 0 1-2.57-4.27");
}

.ueusqblia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.88 41.574h3.632a2.724 2.724 0 0 0 2.724-2.723V9.149a2.724 2.724 0 0 0-2.724-2.723H28.88");
}

.vc80y3b8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.864 41.574h1.016a2.724 2.724 0 0 0 2.724-2.723V9.149a2.724 2.724 0 0 0-2.724-2.723h-1.016m8.28 35.148h3.632a2.724 2.724 0 0 0 2.724-2.723V9.149a2.724 2.724 0 0 0-2.723-2.723h-3.633");
}

</style>
