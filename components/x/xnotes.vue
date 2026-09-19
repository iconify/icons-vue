<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g02v3elwp"/><path class="oa5tpob1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xnotes" /></template>
<style>
.g02v3elwp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.585 9.206l-22.33 29.588m22.33 0L15.255 9.206m22.728-.12H42.5l-3.137 4.743h-5.267m-.242 20.378h-4.517l3.137 4.743h5.267m-22.966 0h-4.517l3.138-4.743h5.267m.323-20.414h4.517L20.366 9.05h-5.267");
}

.oa5tpob1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.827 9.206L10.496 38.794m22.331 0L10.496 9.206m22.729-.12h4.516l-3.136 4.743h-5.268m-.242 20.378H24.58l3.137 4.743h5.267m-22.967 0H5.5l3.137-4.743h5.267m.324-20.414h4.516L15.607 9.05H10.34");
}

</style>
