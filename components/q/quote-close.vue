<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx_ird53q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:quote-close" /></template>
<style>
.rx_ird53q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 4.5q-4 0-4 4t4 4q1.106 0 1.906-.306q-1.176 3.206-4.685 4.61q-.068.027-.13.067t-.115.092t-.094.113t-.071.129q-.029.067-.045.14q-.015.072-.016.146t.013.146q.013.073.041.142q.055.138.159.245t.242.165q.137.059.286.061t.288-.054Q11 15.708 11 8.5q0-4-4-4m10 0q-4 0-4 4t4 4q1.106 0 1.906-.306q-1.176 3.206-4.685 4.61q-.068.027-.13.067t-.115.092t-.094.113t-.071.129q-.029.067-.045.14q-.015.072-.016.146t.013.146q.013.073.041.142q.027.068.067.13t.092.115t.113.094q.061.042.129.071q.067.029.14.045q.072.015.146.016t.146-.013t.142-.041Q21 15.708 21 8.5q0-4-4-4");
}

</style>
