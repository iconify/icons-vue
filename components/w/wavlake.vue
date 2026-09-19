<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t_q0h8e1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wavlake" /></template>
<style>
.t_q0h8e1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.59 8.803h7.334v25.97a3.67 3.67 0 0 1-3.667 3.667h0a3.67 3.67 0 0 1-3.667-3.667zm37 9.43H32.3l-8.364 9.409v-9.41h-7.335v16.54a3.667 3.667 0 0 0 3.668 3.668a3.65 3.65 0 0 0 2.663-1.158l.004.003z");
}

</style>
