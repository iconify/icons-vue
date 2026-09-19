<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rsby0-u3v"/><circle transform="rotate(-.71 24 23.999)" class="c7v45dy1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:refind" /></template>
<style>
.c7v45dy1s {
  cx: 24px;
  cy: 23.999px;
  r: 9.406px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rsby0-u3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.488 42.172c-9.271 5.86-21.467 3.803-28.302-4.774S1.068 16.472 8.85 8.744C16.633 1.016 28.985.384 37.515 7.28s10.502 19.106 4.576 28.335");
}

</style>
