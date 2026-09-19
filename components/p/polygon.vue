<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c23pli_oz"/><path class="fztiq44oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:polygon" /></template>
<style>
.c23pli_oz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5v13h13zm0 0v13H11zm0 26v-13H11zm0 13v-13H11zm0-13v-13h13z");
}

.fztiq44oj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 17.5v13h13z");
}

</style>
