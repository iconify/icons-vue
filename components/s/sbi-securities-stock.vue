<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dgx9w5zxb"/><circle class="tav-gubox"/><circle class="awdcneboh"/><path class="mx7lyqzxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sbi-securities-stock" /></template>
<style>
.awdcneboh {
  cx: 24px;
  cy: 30.113px;
  r: 3.258px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dgx9w5zxb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.342 4.5v9.683m-5.369-4.842a2.42 2.42 0 0 1 0 4.842H23.98V4.5h3.994a2.42 2.42 0 0 1 0 4.841m-.001 0h-3.994m-9.129 3.781c.593.773 1.338 1.06 2.374 1.06h1.433a2.416 2.416 0 0 0 2.416-2.415v-.01a2.416 2.416 0 0 0-2.416-2.416h-1.581a2.42 2.42 0 0 1-2.418-2.418A2.423 2.423 0 0 1 17.08 4.5h1.426c1.036 0 1.78.288 2.374 1.06");
}

.mx7lyqzxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 33.371V43.5");
}

.tav-gubox {
  cx: 24px;
  cy: 30.113px;
  r: 13.387px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
