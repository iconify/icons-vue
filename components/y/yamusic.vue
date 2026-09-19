<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e8i2-h4lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yamusic" /></template>
<style>
.e8i2-h4lm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.91 4.5v17.85a7.57 7.57 0 1 0 2.24 5.38V13.61l11 3.4V9ZM23 12h-.07a15.77 15.77 0 1 0 15.44 15.72");
}

</style>
