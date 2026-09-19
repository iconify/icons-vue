<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="dv4up9dzy"/><path class="svmkcrb6v"/></g><circle class="iv34yub_k"/><path class="fiqpmub9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opera-mini" /></template>
<style>
.dv4up9dzy {
  d: path("M32.669 42.373q-1.442.286-2.957.288c-5.12 0-9.705-2.54-12.79-6.545v0c-2.376-2.806-3.916-6.954-4.021-11.61v-1.012c.104-4.655 1.644-8.804 4.022-11.61C20.006 7.878 24.592 5.34 29.71 5.34c3.15 0 6.096.961 8.616 2.634A21.4 21.4 0 0 0 24.08 2.502L24 2.501C12.125 2.5 2.5 12.127 2.5 24c0 11.528 9.077 20.938 20.476 21.472q.509.026 1.024.026c3.384 0 6.585-.782 9.432-2.175");
}

.fiqpmub9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35 41.992v-6.993l3.5 7L42 35.01v6.989");
}

.iv34yub_k {
  cx: 38.5px;
  cy: 38.499px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.svmkcrb6v {
  d: path("M43.326 33.432A21.4 21.4 0 0 0 45.5 24c0-6.368-2.77-12.089-7.17-16.026c-2.521-1.672-5.468-2.634-8.618-2.634c-5.12 0-9.705 2.54-12.79 6.545c1.973-2.329 4.522-3.733 7.306-3.733c4.478 0 8.35 3.634 10.19 8.91c.732 2.095 1.142 4.45 1.142 6.939c0 8.752-5.073 15.848-11.333 15.848c-2.783 0-5.332-1.404-7.304-3.733c3.084 4.006 7.67 6.545 12.79 6.545c1.008 0 1.996-.099 2.956-.287");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
