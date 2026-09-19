<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lnjcze4se"/><path class="gdzem4b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:piccoma" /></template>
<style>
.gdzem4b5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.94 31.91c10.854-4.058 12.213-13.12 12.674-17.385m-9.106 2.389l1.638 3.932m-9.686.075l3.568.202l-2.467 2.792");
}

.lnjcze4se {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.265 6.515L4.5 17.977l8.807 19.806l17.381-3.465l-.361 7.167l4.779-7.937l3.978-.773l4.416-15.95z");
}

</style>
