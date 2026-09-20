<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="na5onn0lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:saymee" /></template>
<style>
.na5onn0lw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.265 27.913H6.422m11.15-7.824H6.601m-.187 7.825a3.914 3.914 0 1 1 0-7.828M21.467 24a3.914 3.914 0 1 1-3.914-3.914A3.914 3.914 0 0 1 21.467 24m19.831 3.913H30.455m11.15-7.824H30.634m-.187 7.825a3.914 3.914 0 1 1 0-7.828M45.5 24a3.914 3.914 0 0 1-7.829 0a3.914 3.914 0 0 1 7.829 0");
}

</style>
