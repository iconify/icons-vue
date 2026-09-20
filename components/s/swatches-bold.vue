<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zjduxcbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:swatches-bold" /></template>
<style>
.zjduxcbvn {
  fill: currentColor;
  d: path("M242.79 149.32L223.7 97.11a20 20 0 0 0-25.58-11.91l-61.31 22.22l10.89-62.24A20 20 0 0 0 131.55 22l-54.68-9.69a19.94 19.94 0 0 0-23.11 16.24l-25 143.13a48 48 0 0 0 38.64 55.58a51 51 0 0 0 8.7.74H224a20 20 0 0 0 20-20v-51.81a21.7 21.7 0 0 0-1.21-6.87M99 184.18a23.84 23.84 0 0 1-9.86 15.56a23.28 23.28 0 0 1-17.56 3.89a24 24 0 0 1-19.23-27.82L76.71 36.66L123.37 45zm23.64 4.13l9.39-53.64l70.49-25.54l16.3 44.59l-96.23 34.87c.03-.09.06-.18.07-.28ZM220 204h-69.48L220 178.82ZM89.22 174.07l-1.4 8A12 12 0 0 1 76 192a12.4 12.4 0 0 1-2.08-.18a12 12 0 0 1-9.75-13.89l1.4-8a12 12 0 0 1 23.64 4.14Z");
}

</style>
