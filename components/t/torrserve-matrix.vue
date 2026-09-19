<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="w2supkbvj"/><circle class="r3r4_5bea"/><path class="q-aejebst"/><path class="l7xcjnbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:torrserve-matrix" /></template>
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

.l7xcjnbeh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.001 4.983l-8.344 13.586l6.142-1.522l-7.924 10.108l4.931-.566L13.41 42.715l7.839-12.276l-5.046.726l6.48-9.625l-4.793.856z");
}

.q-aejebst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.785 26.918a2.84 2.84 0 0 1 2.635-1.754h1.67c1.213 0 2.085.332 2.78 1.223m-7.063 8.716c.695.891 1.567 1.223 2.78 1.223h1.68c1.562 0 2.828-1.247 2.828-2.784v-.013c0-1.537-1.266-2.784-2.829-2.784h-1.852a2.84 2.84 0 0 1-2.377-1.272");
}

.r3r4_5bea {
  cx: 24px;
  cy: 24px;
  r: 17.921px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w2supkbvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.814 13.158h7.739m-3.869 11.484V13.158");
}

</style>
