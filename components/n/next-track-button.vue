<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="y94jm1b4c"><path class="b9aqm66oi"/><path class="unsl_58gz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:next-track-button" /></template>
<style>
.b9aqm66oi {
  d: path("m6.24 95.18l48.94-28.26v28.26L109.17 64L55.18 32.82v28.26L6.24 32.82z");
}

.unsl_58gz {
  d: path("M104.18 33.23h17.58v61.54h-17.58z");
}

.y94jm1b4c {
  fill: var(--svg-color--40c0e7, #40c0e7);
}

</style>
