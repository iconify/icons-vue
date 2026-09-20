<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cm5cjov7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sword-of-elpisia" /></template>
<style>
.cm5cjov7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.212 28.82c1.527 1.833 3.36 2.749 6.108 2.749h3.665c3.36 0 6.109-2.748 6.109-6.108s-2.75-6.108-6.11-6.108h-3.969c-3.36 0-6.109-2.749-6.109-6.108c0-3.36 2.75-6.109 6.109-6.109h3.665c2.748 0 4.58.612 6.108 2.75M42.5 34.726l-37 .092m29.582-6.18v12.225");
}

</style>
