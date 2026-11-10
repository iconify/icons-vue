<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g4j6-v00w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stafflinq" /></template>
<style>
.g4j6-v00w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.957 38.142A18.36 18.36 0 0 1 2.58 25.159h18.36zM2.58 22.841c0-4.87 1.934-9.54 5.377-12.983L20.94 22.841zM40.043 9.858a18.36 18.36 0 0 1 5.378 12.983H27.06zm5.377 15.301c0 4.87-1.934 9.54-5.377 12.983L27.06 25.159zM9.858 7.957A18.36 18.36 0 0 1 22.841 2.58v18.36zM25.159 2.58c4.87 0 9.54 1.934 12.983 5.377L25.159 20.94zm12.983 37.463c-3.44 3.435-8.122 5.346-12.983 5.378V27.06zM22.841 45.42a18.36 18.36 0 0 1-12.983-5.377L22.841 27.06z");
}

</style>
