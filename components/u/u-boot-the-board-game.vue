<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mrckpdx9d"/><path class="hmogou10c"/><path class="dnw81-bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:u-boot-the-board-game" /></template>
<style>
.dnw81-bye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.697 21.304V16.15s.13-1.66 1.615-1.703");
}

.hmogou10c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.787 24.233l2.053-2.93h8.341l2.315 2.93m-6.769-2.929v-2.227");
}

.mrckpdx9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 29.992v-3.617m0 1.809l13.296-3.912s19.12-.087 22.578 0c6.766.174 6.903 7.513 0 7.557c-4.409.026-22.317 0-22.317 0zm2.946-1.029l.83-4.498h3.012v3.282m-3.842 3.116l.83 4.498h3.012V30.27");
}

</style>
