<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kunwvzqto"/><path class="pqf239bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:psb" /></template>
<style>
.kunwvzqto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 5.5L5.5 17.833V42.5h12.333l12.333-12.333H17.833z");
}

.pqf239bdr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 42.5L42.5 30.167V5.5H30.167L17.834 17.833h12.333z");
}

</style>
