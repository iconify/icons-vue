<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wimltc6pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:omega-20-regular" /></template>
<style>
.wimltc6pt {
  fill: currentColor;
  d: path("M10 2a8 8 0 0 1 8 8c0 2.035-1.096 3.748-2.24 4.986A14.3 14.3 0 0 1 13.423 17H17.5a.5.5 0 0 1 0 1h-4.684a.817.817 0 0 1-.812-.733L12 17.184l.007-.107a.82.82 0 0 1 .384-.595l.432-.283a13.4 13.4 0 0 0 2.202-1.89C16.095 13.15 17 11.67 17 10a7 7 0 1 0-14 0c0 1.67.906 3.15 1.975 4.308a13.4 13.4 0 0 0 2.634 2.174c.242.15.391.414.391.702c0 .45-.366.816-.816.816H2.5a.5.5 0 0 1 0-1h4.078c-.593-.41-1.494-1.1-2.339-2.015C3.096 13.747 2 12.035 2 10a8 8 0 0 1 8-8");
}

</style>
