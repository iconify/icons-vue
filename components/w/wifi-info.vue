<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ixmqs7_tv"/><path class="i9clfwm2k"/><circle class="bh3_y9bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wifi-info" /></template>
<style>
.bh3_y9bcu {
  cx: 23.91px;
  cy: 19.215px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ixmqs7_tv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.595 18.816c2.538-2.658 6.783-4.26 11.337-4.281s8.827 1.543 11.415 4.177m-22.847.266l11.437 14.488L35.5 18.876m-11.59 3.295v4.642");
}

</style>
