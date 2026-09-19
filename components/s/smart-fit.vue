<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u9mib9b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smart-fit" /></template>
<style>
.u9mib9b9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.886c-6.17 3.76-12.793 5.718-19.49 5.762c-6.704-.044-13.335-2.007-19.51-5.775c5.274 6.399 12.075 10.254 19.504 10.254c7.424 0 14.224-3.85 19.496-10.242Z");
}

</style>
