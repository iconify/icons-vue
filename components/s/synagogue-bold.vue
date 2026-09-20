<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ey2xqebqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:synagogue-bold" /></template>
<style>
.ey2xqebqw {
  fill: currentColor;
  d: path("M208 54.34V32a12 12 0 0 0-24 0v22.34A32.06 32.06 0 0 0 164 84v26.75L140 97V72a12 12 0 0 0-24 0v25l-24 13.75V84a32.06 32.06 0 0 0-20-29.66V32a12 12 0 0 0-24 0v22.34A32.06 32.06 0 0 0 28 84v132a12 12 0 0 0 12 12h176a12 12 0 0 0 12-12V84a32.06 32.06 0 0 0-20-29.66M128 160a12 12 0 0 0-12 12v32H92v-65.61l36-20.57l36 20.57V204h-24v-32a12 12 0 0 0-12-12M52 84a8 8 0 0 1 16 0v16H52Zm136 0a8 8 0 0 1 16 0v16h-16ZM52 124h16v80H52Zm136 80v-80h16v80Z");
}

</style>
