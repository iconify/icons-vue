<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ht8mw2b7x"/><path class="hev4cy03k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ziggo-go" /></template>
<style>
.hev4cy03k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.955 14.715H30.31c1.098 0 1.648 1.328.872 2.104L16.819 31.181c-.776.776-.226 2.104.872 2.104h13.788");
}

.ht8mw2b7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.34 8.493A6.78 6.78 0 0 0 35.712 5.5H12.29a6.79 6.79 0 0 0-6.79 6.789v23.422c0 3.75 3.04 6.789 6.789 6.789h23.422c3.75 0 6.789-3.04 6.789-6.789V13.747");
}

</style>
