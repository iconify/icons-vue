<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="usoaosboa"/><path class="fvkq1jbyt"/><path class="w802l6bvu"/><path class="h0hgh6bxd"/><path class="d35hfzbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:regioradstuttgart" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d35hfzbcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.74 25.264l7.104 5.16m-8.18-4.378l1.451 4.47m-2.779-4.47l-1.34 4.128m.264-4.91l-4.635 3.367M12.54 24H4.648m17.201 0H17.56m-4.907-8.243l-4.31-3.13M22.26 22.736l-4.764-3.46m5.84 2.678l-5.311-16.36m6.639 16.36l5.311-16.36M25.74 22.736l13.916-10.109");
}

.fvkq1jbyt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.043 31.997c12.407-3.43 23.613-1.312 26.809-.787");
}

.h0hgh6bxd {
  fill: currentColor;
  d: path("M24 24.75a.75.75 0 0 1 0-1.5a.75.75 0 0 1 0 1.5");
}

.usoaosboa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.865 45.15c4.33-5.94 10.834-9.411 14.668-10.251M22.845 45.47c6.43-8.025 19.198-13.374 21.189-13.666M18.981 44.907c6.297-6.5 16.904-13.388 25.664-14.902M15.6 43.792c5.995-5.53 18.387-13.981 29.411-15.228M13.11 42.538c9.867-9.34 23.266-14.247 32.156-15.37");
}

.w802l6bvu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.138 30.136l-.218-15.919l1.096-.343l.272-3.438l-2.197-.199l-.041-4.284l-.041 4.284l-2.197.199l.272 3.438l1.096.343l-.22 16.044M26.151 24h17.2");
}

</style>
