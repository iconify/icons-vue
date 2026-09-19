<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wdquc1w1p"/><circle class="gt5aqp56v"/><path class="q3gjr03lk"/><path class="i8hj1sbqw"/><path class="whunzzb3y"/><path class="zvq2e8zkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wordle" /></template>
<style>
.gt5aqp56v {
  cx: 24px;
  cy: 25.241px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i8hj1sbqw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.338 13.739a8.5 8.5 0 0 1 12.526 7.486h0a8.5 8.5 0 0 1-7.312 8.416");
}

.q3gjr03lk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.886 17.552l1.946 7.345l3.554-.963m13.688 13.914l3.798-6.628l2.108 1.226c1.19.693 1.586 2.25.88 3.48s-2.24 1.664-3.432.971l-2.107-1.225m2.108 1.225l.862 3.4m-9.61-26.737l1.721-1.721m3.613 1.78l-2.638 2.637l-5.392-5.392l2.638-2.638M16.73 39.692l-3.794-6.6l1.447-.84c1.553-.9 3.555-.338 4.471 1.257l.474.825c.917 1.595.4 3.618-1.152 4.519zm20.607-22.143c1.305.35 2.066 1.716 1.705 3.064l-.665 2.48c-.36 1.347-1.703 2.15-3.009 1.801s-2.066-1.717-1.705-3.065l.665-2.479c.36-1.348 1.703-2.151 3.009-1.802");
}

.wdquc1w1p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.605 33.699c.168.673.253 1.365.253 2.06h0a8.5 8.5 0 1 1-14.387-6.132");
}

.whunzzb3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.232 27.28a8.5 8.5 0 0 1 7.908 8.479h0a8.5 8.5 0 0 1-16.152 3.7m-7.846-11.026a8.5 8.5 0 1 1-.495-14.703");
}

.zvq2e8zkw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.53 18.748A8.5 8.5 0 1 1 32.5 12.24h0a8.5 8.5 0 0 1-3.026 6.502m-1.754 2.694l-1.86 7.613L24 21.436l-1.86 7.613l-1.861-7.613");
}

</style>
