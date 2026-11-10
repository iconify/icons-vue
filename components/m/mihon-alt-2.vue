<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qirj9qbuy"/><path class="tkdwp8lsw"/><path class="xm9uzjeuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mihon-alt-2" /></template>
<style>
.qirj9qbuy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.492 18.888c-.049 6.13-.414 9.247-5.748 13.252");
}

.tkdwp8lsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.264 15.937c3.605 0 4.91.084 7.051-.605l-3.777 11.432c-1.833 5.546-5.158 5.057-5.729 1.916c-.5-2.752 1.318-6.065 5.997-5.76c4.568.296 8.415 1.645 12.573 4.361");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
