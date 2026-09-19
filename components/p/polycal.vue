<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="drcn-fb9d"/><path class="ew-i9_keu"/><path class="s177feg2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:polycal" /></template>
<style>
.drcn-fb9d {
  d: path("M17.353 31.024s-1.58 3.335.015 4.001c2.62 1.09 3.498-8.915 2.41-17.433M33.616 30.79s-.16 4.68-4.048 4.154c-4.072-.555-3.58-10.917-2.492-16.848");
}

.ew-i9_keu {
  d: path("M12.556 20.728s2.188-3.089 7.792-3.627c5.99-.574 12.987 2.89 13.69.39c.44-1.79-1.58-2.234-3.663-1.054");
}

.s177feg2o {
  d: path("M10.177 7.857a4 4 0 0 0-4 4v27.646a4 4 0 0 0 4 4h27.646a4 4 0 0 0 4-4V11.857a4 4 0 0 0-4-4zM12.8 10.3V4.5m22.4 5.8V4.5m-16.8 5.8V4.5m5.6 5.8V4.5m5.6 5.8V4.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
