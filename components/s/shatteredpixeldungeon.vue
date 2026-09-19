<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sckal9txw"/><path class="do-23bc_q"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shatteredpixeldungeon" /></template>
<style>
.do-23bc_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.979 39v-1.979h3.959v-1.98h3.959v1.98h1.979m-7.917-5.939h1.979v3.959M39 10.57h-1.57v3.14h-1.57v1.57h-3.14v3.141h-1.571m-1.57-4.711h1.57v1.57h1.571");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.sckal9txw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39 22h-7.917v-5.08h-5.082V9H38a1 1 0 0 1 1 1zm-11.917-1.082v6.166h-6.166v-6.166zM22.001 9v7.92h-3.979l-1.105-.003V22H9V10a1 1 0 0 1 1-1zM38 39H10a1 1 0 0 1-1-1V26h7.917v5.083h14.166V26H39v12a1 1 0 0 1-1 1");
}

</style>
