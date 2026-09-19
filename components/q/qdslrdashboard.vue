<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jw212emya"/><path class="d1n98rbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qdslrdashboard" /></template>
<style>
.d1n98rbmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.83 9.175l-2.77 2.84H6.29a1.79 1.79 0 0 0-1.79 1.79v23.22a1.8 1.8 0 0 0 1.79 1.8h35.42a1.8 1.8 0 0 0 1.79-1.8v-23.22a1.79 1.79 0 0 0-1.79-1.79H30.94l-2.77-2.84Z");
}

.jw212emya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.115a8.51 8.51 0 1 1-8.51 8.51h0a8.51 8.51 0 0 1 8.51-8.51m-9.279-3.172a1.84 1.84 0 0 1 .003 3.68h-.003a1.84 1.84 0 0 1 0-3.68");
}

</style>
