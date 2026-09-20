<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ca1glgldo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:up-right-arrow" /></template>
<style>
.ca1glgldo {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M98.18 29.76L89.9 83.49L75.72 69.31L46.78 98.24L29.82 81.28l28.94-28.93l-14.32-14.33z");
}

</style>
