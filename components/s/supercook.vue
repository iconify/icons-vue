<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rs6a89h-z"/><path class="vtz10d15p"/><path class="qgl2zcc9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:supercook" /></template>
<style>
.qgl2zcc9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.719 25.025c.029 3.012 2.979 4.423 2.979 4.423");
}

.rs6a89h-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.6 30.698l.001 11.802h2.285V32.106m.33-10.666c-.796 2.2 1.886 2.669 5.28 2.885c0 0 18.873.287 21.693 2.774c-13.593-4.438-16.123 1.459-16.727 7.041");
}

.vtz10d15p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.26 21.44c-4.618.472-5.322 12.444 13.203 12.7M11.26 21.44c-1.093-2.19-4.45-2.108-4.45-5.847C6.812 11.153 9.468 5.5 12.744 5.5s5.933 5.654 5.933 10.093c0 3.747-3.373 3.642-4.46 5.847m-2.957 0h2.956");
}

</style>
