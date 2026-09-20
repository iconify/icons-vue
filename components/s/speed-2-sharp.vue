<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t41kff6th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-2-sharp" /></template>
<style>
.t41kff6th {
  fill: currentColor;
  d: path("M13.208 15.175q.476-.477.436-1.144t-.586-1.064q-1.822-1.338-3.716-2.673T5.63 7.662q1.292 1.825 2.646 3.716t2.675 3.697q.404.552 1.083.574t1.175-.474M4.458 19q-.702-1.287-1.086-2.454q-.383-1.167-.378-2.657q0-1.847.732-3.47t1.965-2.83t2.87-1.898T12 5q1.864 0 3.503.71q1.64.711 2.858 1.93t1.929 2.857Q21 12.137 21 14q0 1.466-.397 2.599T19.503 19z");
}

</style>
