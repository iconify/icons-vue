<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj5s-5-4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-airline-seat-flat-angled" /></template>
<style>
.kj5s-5-4c {
  fill: currentColor;
  d: path("M21.56 16.18L9.2 11.71l2.08-5.66l12.35 4.47zM1.5 12.14L8 14.48V19h8v-1.63L20.52 19l.69-1.89l-19.02-6.86zm5.8-1.94a3.01 3.01 0 0 0 1.41-4A3.005 3.005 0 0 0 4.7 4.8a2.99 2.99 0 0 0-1.4 4a2.99 2.99 0 0 0 4 1.4");
}

</style>
