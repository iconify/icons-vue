<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dlms10t4t"/><path class="hidckwbrk"/><path class="oweicmbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mt-capsule" /></template>
<style>
.dlms10t4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.918 22.147a2.123 2.123 0 0 1-2.141-2.105a2.123 2.123 0 0 1 2.11-2.136a2.123 2.123 0 0 1 2.139 2.207a2.106 2.106 0 0 1-2.108 2.034m12.302 0a2.123 2.123 0 0 1-2.14-2.105a2.123 2.123 0 0 1 2.11-2.136a2.123 2.123 0 0 1 2.139 2.207a2.106 2.106 0 0 1-2.109 2.034");
}

.hidckwbrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.035 9.165c8.321 0 15.067 6.73 15.067 15.034v0a2.14 2.14 0 0 1-2.143 2.138H11.041a2.14 2.14 0 0 1-2.143-2.138v0c0-8.303 6.746-15.034 15.067-15.034zM11.04 6.923l4.286 5.018m21.737-5.018l-4.268 5.018m10.411 13.017l.552.307a2.41 2.41 0 0 1 .935 3.29l-.888 1.593a2.41 2.41 0 0 1-3.29.935l-.551-.308a2.41 2.41 0 0 1-.935-3.289l.888-1.593a2.41 2.41 0 0 1 3.29-.935m-38.413 0l-.552.307a2.41 2.41 0 0 0-.935 3.29l.888 1.593a2.41 2.41 0 0 0 3.29.935l.551-.308a2.41 2.41 0 0 0 .935-3.289l-.888-1.593a2.41 2.41 0 0 0-3.29-.935");
}

.oweicmbyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.268 28.864a5.5 5.5 0 0 1 1.681-.263v0h26.102c.587 0 1.152.093 1.681.263m3.071 2.52c.438.785.688 1.69.688 2.657v1.596a5.43 5.43 0 0 1-5.44 5.44H10.949a5.43 5.43 0 0 1-5.44-5.44V34.04c0-.966.25-1.872.688-2.657");
}

</style>
