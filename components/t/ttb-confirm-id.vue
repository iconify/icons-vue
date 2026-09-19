<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rhm7kcbfr"/><path class="nk3s9bccx"/><path class="ksjnacb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ttb-confirm-id" /></template>
<style>
.ksjnacb2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.893 22.501l2.194 4.014l8.87-8.06");
}

.nk3s9bccx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.797 25.766c-.326 3.71-3.485 6.623-7.333 6.623h-3.786V15.8h3.786a7.38 7.38 0 0 1 6.433 3.727");
}

.rhm7kcbfr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.652 41.96a2.81 2.81 0 0 1-2.817-2.803V8.858A2.81 2.81 0 0 1 8.637 6.04h30.711a2.81 2.81 0 0 1 2.818 2.803v22.788c.012 5.691-4.592 10.315-10.283 10.327h-.045zm7.388-26.161v16.59");
}

</style>
