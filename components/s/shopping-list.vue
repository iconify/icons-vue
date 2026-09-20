<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ac_g-pbug"/><path class="y0vmj5buy"/></g><path class="ahoyuvb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shopping-list" /></template>
<style>
.ac_g-pbug {
  d: path("M24 4.5a2.62 2.62 0 0 0-2.617 2.614H10.46c-.914 0-1.65.735-1.65 1.649v33.089c0 .913.736 1.648 1.65 1.648h27.078c.914 0 1.65-.735 1.65-1.648V8.762c0-.913-.736-1.648-1.65-1.648H26.617A2.62 2.62 0 0 0 24 4.5");
}

.ahoyuvb2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.209 15.166H30.79m-13.581 4.272H30.79m-17.472 4.445h1.044c.914 0 1.472.752 1.649 1.648l1.52 7.696c.32 1.622 1.24 2.346 2.8 2.346h7.778c1.561 0 2.48-.724 2.801-2.346l1.442-7.302l.035-.177H16.104m6.47 2.798h3.76m1.919 9.967a.766.766 0 1 1-1.532 0a.766.766 0 0 1 1.532 0m-6.473 0a.766.766 0 0 1-1.532 0a.766.766 0 0 1 1.533 0");
}

.y0vmj5buy {
  d: path("M29.985 7.115v3.372h-11.97V7.115");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
