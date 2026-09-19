<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qs0ex0v_r"/><path class="rxd-8qbxt"/><path class="fz6wbzbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tap-tap" /></template>
<style>
.fz6wbzbgk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.218 24.307v-5.252a2.394 2.394 0 1 0-4.775 0v5.146");
}

.qs0ex0v_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.443 29.827v5.487c-2.113-1.22-9.03-1.82-5.571 2.274s5.117 5.912 6.48 5.912h10.802c2.046 0 1.932-5.798 2.501-7.618s.568-3.639-1.478-4.434c-1.31-.51-2.912-1.76-4.724-2.598M16.61 17.292a7.39 7.39 0 1 1 9.608 7.014v3.73a7.75 7.75 0 0 1 3.235.813a12.772 12.772 0 1 0-8.012.977V24.2a7.37 7.37 0 0 1-4.832-6.909Z");
}

.rxd-8qbxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.392 17.292a7.39 7.39 0 1 0-9.95 6.91v-5.147a2.394 2.394 0 1 1 4.775 0v5.252a7.37 7.37 0 0 0 5.174-7.014Z");
}

</style>
