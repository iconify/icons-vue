<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r8yo86o1v"/><path class="rt1yb1liv"/><circle class="b7zbuj9kt"/><path class="pkb7zz_3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sd-maid-pro" /></template>
<style>
.b7zbuj9kt {
  cx: 37.895px;
  cy: 35.641px;
  r: 8.267px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pkb7zz_3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.401 32.005a2.13 2.13 0 1 1-2.13 2.13a2.13 2.13 0 0 1 2.13-2.13m-1.506 3.636l-3.24 3.241m.815-.816l.998.999");
}

.r8yo86o1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.658 36.338a3.6 3.6 0 0 1-2.138-1.108a3.6 3.6 0 0 1-7 0A3.57 3.57 0 0 1 14.37 32a3.3 3.3 0 0 1-.7.07a3.6 3.6 0 0 1-3.6-3.59h0v-.14H5.51V40a1.94 1.94 0 0 0 1.88 2h25.223M7.501 16.18a18.4 18.4 0 0 0-1.971 8.33v3.8h28.542M12.224 8.474L10.68 6.93A3.22 3.22 0 0 0 8.5 6a3 3 0 0 0-2.12 5.15l.356.348M42.53 28.795V24.51A18.57 18.57 0 0 0 39 13.72l2.58-2.56a3.016 3.016 0 0 0-4.27-4.26h0l-2.55 2.6a18.39 18.39 0 0 0-19.04-1.502m3.41 12.722a2.93 2.93 0 1 1-2.94-2.92h.01a2.93 2.93 0 0 1 2.94 2.9Zm12.65 2.92a2.92 2.92 0 1 1 2.92-2.92h0a2.92 2.92 0 0 1-2.91 2.9Z");
}

.rt1yb1liv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.267 5.76l3.656 5.628l-5.906 1.362l-3.646 4.842l-3.656-5.628l5.906-1.362Z");
}

</style>
