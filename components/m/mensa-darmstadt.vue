<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n0sozfbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mensa-darmstadt" /></template>
<style>
.n0sozfbqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5c-3.805 2.021-11.415 6.183-11.415 6.183v12.841L24 30.183L12.585 36.84L24 43.5l11.415-6.659V23.524l-11.332-6.448l11.332-6.393z");
}

</style>
