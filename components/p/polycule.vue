<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aeexfbztz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:polycule" /></template>
<style>
.aeexfbztz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 12h6l-6.75 12l3.9 6.975L28.35 12h6.15l6.75 12l-6.75 12h-6l6.75-12l-3.9-6.9L19.725 36h-6.3L6.75 24z");
}

</style>
