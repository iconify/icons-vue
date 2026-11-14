<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy9wiebsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:paint-bucket" /></template>
<style>
.vy9wiebsl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.253 3.506Q3.75 5.342 3.75 8q0 .045.005.089v.001L5.25 20.548Q5.274 22.25 7 22.25h10q1.726 0 1.75-1.702L20.245 8.09v-.005q.005-.043.005-.085q0-2.658-2.503-4.494Q15.352 1.75 12 1.75T6.253 3.506M18.672 7.25H5.328q.306-1.43 1.812-2.534Q9.139 3.25 12 3.25t4.86 1.466q1.506 1.104 1.812 2.534m-6.377 4.061q3.205 1.373 6.41 0q.137-.059.286-.061t.288.054q.138.055.245.159t.165.242q.029.067.045.14q.015.072.016.146t-.013.146t-.041.142q-.027.068-.067.13t-.092.115t-.113.094t-.129.071q-3.795 1.627-7.59 0q-3.205-1.373-6.41 0q-.067.029-.14.045q-.072.015-.146.016t-.146-.013q-.073-.013-.142-.041q-.068-.027-.13-.067t-.115-.092t-.094-.113t-.071-.129t-.045-.14t-.016-.146t.013-.146t.041-.142q.027-.068.067-.13t.092-.115t.113-.094t.129-.071q3.795-1.627 7.59 0");
}

</style>
