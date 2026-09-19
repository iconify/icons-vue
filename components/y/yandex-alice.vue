<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="sqm83yb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yandex-alice" /></template>
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

.sqm83yb7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.236 10.945c-1.486.614-2.367 1.692-3.543 3.145s-2.424 3.292-3.607 5.341s-2.153 4.049-2.823 5.793c-.67 1.745-1.163 3.047-.95 4.64a2 2 0 0 0 .763 1.323c1.274.98 2.65 1.206 4.496 1.498s4.062.451 6.428.451s4.582-.159 6.427-.45c1.846-.293 3.222-.519 4.496-1.499a2 2 0 0 0 .764-1.322c.212-1.594-.281-2.896-.951-4.64s-1.64-3.745-2.822-5.794s-2.432-3.89-3.608-5.342c-1.175-1.452-2.056-2.53-3.543-3.144a2 2 0 0 0-1.527 0");
}

</style>
