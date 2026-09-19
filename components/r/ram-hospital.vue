<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nocrnxd3w"/><path class="meq2mybzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ram-hospital" /></template>
<style>
.meq2mybzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.146 30.855H3.622v-13.71h13.525l13.708 13.71m-13.708 0h13.708v13.523h-13.71V33.746");
}

.nocrnxd3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.145 17.147V3.622h13.71v13.525zm13.71-.002h13.523v13.71H30.855z");
}

</style>
