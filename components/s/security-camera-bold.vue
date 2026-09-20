<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oypjlzbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:security-camera-bold" /></template>
<style>
.oypjlzbgb {
  fill: currentColor;
  d: path("M244 132a12 12 0 0 0-12 12v12h-35l-14.35-14.34l47.52-47.52a20 20 0 0 0 0-28.28l-56-56a20 20 0 0 0-28.32 0L6.42 150.47A22 22 0 0 0 22 188h33.7l26.14 26.14a20 20 0 0 0 28.29 0l55.51-55.51l15.52 15.51a19.86 19.86 0 0 0 14.15 5.86H232v12a12 12 0 0 0 24 0v-48a12 12 0 0 0-12-12M160 29.67l15 15L55.71 164h-28.9ZM96 194.34L77.65 176L192 61.66L210.34 80l-53.17 53.17Z");
}

</style>
