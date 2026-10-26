<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":255};
const content = `<path class="c7wic81lk"/><path class="tiiq3cbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:risc-v-icon" /></template>
<style>
.c7wic81lk {
  fill: var(--svg-color--f5b21b, #f5b21b);
  d: path("M142.582 79.716c0 37.104-22.521 70.643-66.268 78.583l61.732 72.911l5.508-7.777l111.15-157.165V0H74.046c46.015 4.537 68.536 42.613 68.536 79.716");
}

.tiiq3cbmg {
  fill: var(--svg-color--283272, #283272);
  d: path("M15.716 124.597H58.33c31.433 0 47.15-22.359 47.15-44.88S89.761 35.97 58.328 35.97H0v218.896h108.881L15.716 142.582zm158.3 118.927L256 128.972v125.732h-90.086z");
}

</style>
