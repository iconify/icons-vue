<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="uv62bp4te"/><circle class="l92ccq9bf"/><circle class="wmtf43bbd"/><circle class="k5mhzrb5k"/><path class="vreai2d1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:medilog" /></template>
<style>
.k5mhzrb5k {
  cx: 40px;
  cy: 27.094px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l92ccq9bf {
  cx: 20.5px;
  cy: 30px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uv62bp4te {
  cx: 8px;
  cy: 18px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vreai2d1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.523 20.422l7.453 7.155m15.011-4.757l4.026 2.454m-13.974 2.321l4.421-4.189");
}

.wmtf43bbd {
  cx: 30px;
  cy: 21px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
