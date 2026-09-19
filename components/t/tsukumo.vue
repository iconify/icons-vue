<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t8j5vgbfq"/><path class="x6v34q0aw"/><path class="z8zmtkrbd"/><circle class="smuubkbob"/><circle class="zxgqhniey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tsukumo" /></template>
<style>
.smuubkbob {
  cx: 27.03px;
  cy: 21.714px;
  r: 0.75px;
  fill: currentColor;
}

.t8j5vgbfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.022 11.999l23.814-6.381a3.393 3.393 0 0 1 4.165 2.404l6.381 23.814a3.393 3.393 0 0 1-2.404 4.165l-23.814 6.381a3.393 3.393 0 0 1-4.165-2.404L5.618 16.164a3.393 3.393 0 0 1 2.404-4.165");
}

.x6v34q0aw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.235 14.465c3.485 3.116 4.393 11.845 4.426 14.386s1.642 9.237 9.487 7.332c7.845-1.904 9.474-8.288 5.791-15.35c-1.351-2.592-.299-4.43-.299-4.43");
}

.z8zmtkrbd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.714 28.757c1.247 2 6.427 6.38 7.636 5.76s4.987-7.169 5.288-10.426");
}

.zxgqhniey {
  cx: 19.714px;
  cy: 25.347px;
  r: 0.75px;
  fill: currentColor;
}

</style>
