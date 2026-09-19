<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ea4o83-sj"/><path class="wzmz1idsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rocket" /></template>
<style>
.ea4o83-sj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.896 22.443L42.105 5.5l-10.836 37l-11.453-13.323z");
}

.wzmz1idsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.326 16.95l-11.51 12.227v8.747l3.316-4.824");
}

</style>
