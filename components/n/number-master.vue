<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="mlxjwbb9y"/><path class="uktfxabzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:number-master" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.mlxjwbb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.8 31.089l2-1.089v8m9.35-15.35a2.653 2.653 0 0 1 3.176-2.6c1.111.214 1.999 1.175 2.11 2.302c.082.837-.184 1.664-.762 2.172C24.602 25.464 21.15 28 21.15 28h5.3m6.95-10.675c.553.463 1.15.675 2.489.675h.311a2 2 0 0 0 2-2h0a2 2 0 0 0-2-1.999");
}

.uktfxabzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.4 10.668c.554-.461 1.15-.671 2.49-.668l.31.002a2 2 0 0 1 2 2h0a2 2 0 0 1-2 1.999m-1.537 0H36.2");
}

</style>
