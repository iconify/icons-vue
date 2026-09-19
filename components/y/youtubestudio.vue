<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b80mwc5jw"/><path class="b4ekidbky"/><path class="zxr3jbk2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:youtubestudio" /></template>
<style>
.b4ekidbky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.258 30.5L24 37l-11.258-6.5v-13L24 11l11.258 6.5Z");
}

.b80mwc5jw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.754 34.25L24 44.5L6.247 34.25v-20.5L24 3.5l17.754 10.25Z");
}

.zxr3jbk2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.764 29.03l8.488-5.013l-8.504-5.047Z");
}

</style>
