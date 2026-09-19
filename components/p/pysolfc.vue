<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="v-_mw090a"/><circle class="k3699i3sp"/><circle class="p3wzhmupl"/><path class="dgu9oibdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pysolfc" /></template>
<style>
.dgu9oibdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.777 42.5H15.106c8.836-7.731 8.836-19.88 8.836-19.88s0 12.149 8.835 19.88");
}

.k3699i3sp {
  cx: 33.94px;
  cy: 25.991px;
  r: 7.238px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p3wzhmupl {
  cx: 24px;
  cy: 12.738px;
  r: 7.238px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v-_mw090a {
  cx: 14.06px;
  cy: 25.991px;
  r: 7.238px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
