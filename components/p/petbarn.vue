<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wk_nwbb6h"/><path class="dozev7bzq"/><path class="gz36vsb-g"/><circle class="vwipshb2d"/><path class="eyxvnhmul"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:petbarn" /></template>
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

.dozev7bzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.653 22.332c0 2.072 1.512 2.166 1.512 2.166m7.62 2.39c-1.204 0-2.4-1.382-2.4-1.382m4.623.449c-.775.28-2.783-1.242-2.783-1.242m-1.849-3.502s.654-1.755-2.082-1.755");
}

.eyxvnhmul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.43 21.052s.906-2.157-1.41-2.484");
}

.gz36vsb-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.156 24.489l3.577-2.167l1.634-1.12l1.858-.15l.868 1.13l.411.14c.542.187.84.766.682 1.317l-.075.252s-3.175.784-4.743 2.297c-1.43 1.382-3.848 1.774-3.848 1.774");
}

.vwipshb2d {
  cx: 22.02px;
  cy: 23.032px;
  r: 0.75px;
  fill: currentColor;
}

.wk_nwbb6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.759 15.459L7.5 27.56l6.05 1.634m19.2-7.835l-3.129 8.302l-3.137-8.302m13.605 6.724c-.56.977-1.6 1.58-2.727 1.578a3.137 3.137 0 0 1-3.137-3.138v-2.036a3.138 3.138 0 0 1 6.275 0v1.018h-6.266m-11.803 1.027a3.137 3.137 0 0 1-6.275 0v-2.035c0-1.728 1.4-3.138 3.138-3.138c.43 0 .84.084 1.223.243");
}

</style>
