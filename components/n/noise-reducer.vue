<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="hlcyoj8fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:noise-reducer" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hlcyoj8fp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.798 39.202L39.202 8.798m-36.6 17.295l2.893-3.028l3.084 4.599l3.085-15.477l3.084 23.888l3.084-15.982l3.084 8.468L24 21.103l3.084 5.719l3.084-11.102l3.084 17.831l3.084-23.383l3.085 20.692l3.084-11.047L45.5 24");
}

</style>
