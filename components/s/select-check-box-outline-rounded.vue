<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp18we4jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:select-check-box-outline-rounded" /></template>
<style>
.hp18we4jp {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h12.475q.425 0 .713.288t.287.712t-.288.713t-.712.287H5v14h14v-6.5q0-.425.288-.712T20 11.5t.713.288t.287.712V19q0 .825-.587 1.413T19 21zm6.525-6.8l8.5-8.5q.275-.275.675-.275t.7.275t.3.7t-.3.725L12.225 16.3q-.3.3-.7.3t-.7-.3l-4.25-4.25q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275z");
}

</style>
