<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g-wd1nglq"/><circle class="e984p7m1u"/><path class="s-top4a0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zygiskdetach" /></template>
<style>
.e984p7m1u {
  cx: 33.873px;
  cy: 19.533px;
  r: 9.627px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g-wd1nglq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.342 28.838v6.122a3.58 3.58 0 0 1-3.58 3.58H8.08a3.58 3.58 0 0 1-3.58-3.58V14.473h21.184m-10.261 0v-3.545c0-.81.656-1.467 1.467-1.467h7.062c.81 0 1.467.657 1.467 1.467v3.545");
}

.s-top4a0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.078 23.328l7.591-7.59m-7.591 0l7.591 7.59M26.9 26.506l-10.721-6.725v13.45z");
}

</style>
