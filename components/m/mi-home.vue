<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="grg_h89cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mi-home" /></template>
<style>
.grg_h89cd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.964 29.122a17.4 17.4 0 0 1-.242-2.9V4.5L24 10.94L41.278 4.5v9.444m0 5.96v6.318A17.28 17.28 0 0 1 24 43.5A17.28 17.28 0 0 1 8.215 33.258");
}

</style>
