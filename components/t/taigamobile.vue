<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ac0ojac8n"/><path class="iue_2tb8v"/><path class="bw57xzbza"/><path class="b15-y6saw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:taigamobile" /></template>
<style>
.ac0ojac8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 28.378h9.048l-5.926-10.263");
}

.b15-y6saw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.988 35.98v7.52h6.024v-4.076");
}

.bw57xzbza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14.67h-5.872L24 4.5v31.48H10.475l6.378-11.046");
}

.iue_2tb8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.115h5.872L24 7.944v31.48h13.525l-6.378-11.046M24 24.934h-9.048l5.926-10.264");
}

</style>
