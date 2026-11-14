<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukr365aad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:spring-butterfly" /></template>
<style>
.ukr365aad {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.287 12.094q2.511.744 5.963-.111v1.203q-2.942-.155-4.814 1.06q-2.174 1.41-1.932 3.829q.263 2.631 3.498 2.487q2.431-.108 3.998-1.841q1.567 1.733 3.998 1.841q3.235.144 3.498-2.487q.242-2.419-1.932-3.829q-1.872-1.215-4.814-1.06v-1.203q3.452.855 5.963.111Q22 11.12 22 8q0-4.5-4.25-4.5q-3.432 0-5.75 3.145Q9.682 3.5 6.25 3.5Q2 3.5 2 8q0 3.12 3.287 4.094m.426-1.438Q3.5 10 3.5 8q0-3 2.75-3q2.995 0 5 3.211v2.223q-3.29.888-5.537.222m12.574 0q-2.247.666-5.537-.222V8.211Q14.755 5 17.75 5q2.75 0 2.75 3q0 2-2.213 2.656m-2.222 8.407q-2.078-.092-3.315-1.798v-2.577q2.51-.149 3.998.816q1.407.913 1.256 2.421q-.122 1.219-1.939 1.138m-8.813-3.559q1.488-.965 3.998-.816v2.577q-1.237 1.706-3.315 1.798q-1.817.081-1.939-1.138q-.151-1.508 1.256-2.421");
}

</style>
