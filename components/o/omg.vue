<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="lfbqqvicq"/><path class="du3n19bqs"/><ellipse class="tk7vx0srb"/><path class="bntg4m3nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:omg" /></template>
<style>
.bntg4m3nq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.263 24c0-2.268 1.702-4.107 3.863-4.296c-.898-5.337-3.414-9.186-6.385-9.186C27.018 10.519 24 16.554 24 24s3.018 13.481 6.74 13.481c2.971 0 5.488-3.849 6.386-9.186c-2.16-.188-3.863-2.028-3.863-4.295");
}

.du3n19bqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.763 24c0-2.268 1.702-4.107 3.863-4.296c-.898-5.337-3.414-9.186-6.385-9.186C8.518 10.519 5.5 16.554 5.5 24s3.018 13.48 6.74 13.48c2.972 0 5.488-3.849 6.386-9.186c-2.16-.188-3.863-2.028-3.863-4.295Z");
}

.lfbqqvicq {
  cx: 14.75px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.25px;
  ry: 18.5px;
}

.tk7vx0srb {
  cx: 33.25px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.25px;
  ry: 18.5px;
}

</style>
