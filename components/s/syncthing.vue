<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t672-4bxv"/><circle class="dblm2jiwe"/><path class="zoajneb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:syncthing" /></template>
<style>
.dblm2jiwe {
  cx: 27.32px;
  cy: 25.62px;
  r: 5.06px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t672-4bxv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39 11.56A19.06 19.06 0 0 0 5.52 23.81m34.92 10.74A18.9 18.9 0 0 0 43.63 24a19.4 19.4 0 0 0-.31-3.43M8.05 33.48a19.07 19.07 0 0 0 24.83 7.67");
}

.zoajneb_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.44 11.35a5.06 5.06 0 1 1 0 10.11H40a5.06 5.06 0 0 1-1-9.89a4.8 4.8 0 0 1 1.44-.22m-4.32 20.86a5.06 5.06 0 1 1-1.41.2a5 5 0 0 1 1.41-.2M7.56 23.38a5.2 5.2 0 0 1 1.38.19a5.06 5.06 0 0 1-.87 9.9h-.51a5.05 5.05 0 0 1-2-9.68a4.9 4.9 0 0 1 2-.41m5.03 4.59l9.71-1.76m8.86-3.88l5.35-2.74m-5.97 9.94l2.8 3.51");
}

</style>
