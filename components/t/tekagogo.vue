<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gyix5wb4t"/><path class="jvnonacml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tekagogo" /></template>
<style>
.gyix5wb4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.347 24.443a5.167 5.167 0 1 1 7.307 0l-10.96 10.96");
}

.jvnonacml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.04 31.75c-6.053-6.053-6.053-15.867 0-21.92s15.867-6.053 21.92 0s6.053 15.867 0 21.92L24 42.71");
}

</style>
