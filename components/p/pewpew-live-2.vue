<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="leikorn-n"/><path class="phoqnzu0y"/><circle class="vi_nxfq0r"/><path class="t50h17b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pewpew-live-2" /></template>
<style>
.leikorn-n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.943 40.901l-.943 1.6l-21.528-7.004l19.02.378L42.5 23l-5.063 8.584m1.091-19.081l-19.021-.377L5.5 25L17 5.5z");
}

.phoqnzu0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.75 27.5l2.12-6.802l22.241-2.416l-18.269 12.913z");
}

.t50h17b9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.85 37.15a2.653 2.653 0 0 1 3.176-2.6c1.111.214 1.999 1.175 2.11 2.302c.082.837-.184 1.664-.762 2.172c-1.072.94-4.524 3.476-4.524 3.476h5.3");
}

.vi_nxfq0r {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
