<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o_qplz6qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:philstocks" /></template>
<style>
.o_qplz6qv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.574 43.5h23.344l7.654-19.477L31.96 4.5H8.428l7.966 19.523zm7.82-19.477h23.179");
}

</style>
