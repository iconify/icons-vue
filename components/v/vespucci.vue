<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="kc-t9wbyu"/><path class="ppuvboz1f"/><path class="t_cyvglrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vespucci" /></template>
<style>
.kc-t9wbyu {
  cx: 10.749px;
  cy: 37.066px;
  r: 2.405px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ppuvboz1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.863 32.098L18.327 6.03c.37-.923 1.755-.549 1.61.435l-4.088 27.767s-1.609 9.697-6.964 8.089C3.529 40.71 7.862 32.098 7.862 32.098Z");
}

.t_cyvglrp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.196 32.679l24.636-3.519c.985-.14 1.353 1.245.428 1.612L11.044 42.356");
}

</style>
