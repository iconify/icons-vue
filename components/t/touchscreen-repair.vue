<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="gkbzx0-9v"/><path class="c5k0mdbnp"/><circle class="nb8ocabqb"/><path class="oe4w6sfpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:touchscreen-repair" /></template>
<style>
.c5k0mdbnp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 8h23m0 32h-23m16.806-9.64a2 2 0 0 0 0-2.828l-5.38-5.381l-2.83 2.828l5.382 5.381a2 2 0 0 0 2.828 0m-10.762 0a2 2 0 0 0 2.828 0l1.373-1.373l-2.828-2.828l-1.373 1.373a2 2 0 0 0 0 2.828m5.092-5.67l3.875 3.875m-6.168-6.168l-4.692-4.692m9.583.231a3 3 0 0 0 4.241 4.241a3 3 0 0 0 .55-3.475l-2.012 2.013a.931.931 0 1 1-1.318-1.318l2.017-2.016a3 3 0 0 0-3.478.555");
}

.gkbzx0-9v {
  width: 23px;
  height: 39px;
  x: 12.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.nb8ocabqb {
  cx: 19.938px;
  cy: 28.966px;
  r: 0.75px;
  fill: currentColor;
}

.oe4w6sfpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.644 18.639l-1.993-.935l.934 1.994l1.224.165z");
}

</style>
