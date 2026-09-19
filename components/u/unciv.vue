<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kf2qxbcgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unciv" /></template>
<style>
.kf2qxbcgf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.13 5.45l-5.75 3.32v6.64l5.75 3.32l5.75-3.32V8.77Zm13.74 0l-5.75 3.32v6.64l5.75 3.32l5.76-3.32V8.77ZM10.25 17.36L4.5 20.68v6.64l5.75 3.32L16 27.32v-6.64Zm13.75 0l-5.75 3.32v6.64L24 30.64l5.75-3.32v-6.64Zm13.75 0L32 20.68v6.64l5.75 3.32l5.75-3.32v-6.64Zm-20.62 11.9l-5.75 3.33v6.64l5.75 3.32l5.75-3.32v-6.64Zm13.74 0l-5.75 3.33v6.64l5.75 3.32l5.76-3.32v-6.64Z");
}

</style>
