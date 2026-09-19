<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gx3myzygn"/><path class="s527x4t_d"/><ellipse class="qgdm5ebss"/><path class="tw-k7mmmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nesnezeno" /></template>
<style>
.gx3myzygn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.748 32.272v-12.21l3.043-.299l4.527 5.78l1.053-5.665l4.352-.472V32.45h-3.074l-6.03-5.21l-.575 5.03z");
}

.qgdm5ebss {
  cx: 23.96px;
  cy: 11.663px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.225px;
  ry: 1.093px;
}

.s527x4t_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.815 37.21h38.554c.925-10.749-2.891-19.406-16.467-23.755c3.14-7.604-9.422-6.46-5.817.178C7.04 18.236 4.735 27.273 4.815 37.21");
}

.tw-k7mmmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 39.808h38.797");
}

</style>
