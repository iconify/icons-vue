<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="owr_4mwof"/><path class="jnkd6rbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:office-nx-textmaker" /></template>
<style>
.jnkd6rbbe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.75 24.371l-1.36 5.439a2.56 2.56 0 0 1-2.485 1.94H4.5c1.175 0 2.2-.8 2.485-1.94L9.89 18.19a2.56 2.56 0 0 1 2.485-1.94h.405M4.5 30l3.438-13.75H4.5m1.719 6.875L7.437 28m27.813-4.371l1.36-5.439a2.56 2.56 0 0 1 2.485-1.94H43.5c-1.176 0-2.2.8-2.486 1.94L38.11 29.81a2.56 2.56 0 0 1-2.485 1.94h-.405M43.5 18l-3.437 13.75H43.5m-1.719-6.875L40.562 20m-20-1.125h6.876M24 29.125v-10.25");
}

.owr_4mwof {
  width: 22.5px;
  height: 22.5px;
  x: 12.75px;
  y: 12.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
