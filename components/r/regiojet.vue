<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bmwhhsbrc"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:regiojet" /></template>
<style>
.bmwhhsbrc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.5 17.474l-1.726 9.79c-.318 1.801-2.036 3.262-3.839 3.262s-3.005-1.46-2.687-3.263l.19-1.084M13.5 30.526l2.302-13.052h4.273c2.416 0 4.028 1.962 3.6 4.383c-.426 2.421-2.73 4.384-5.146 4.384h-4.273m4.273 0l3.518 4.282");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
