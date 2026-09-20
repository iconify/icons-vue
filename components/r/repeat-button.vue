<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="y94jm1b4c"><path class="cmum6nbkk"/><path class="bssktkx8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:repeat-button" /></template>
<style>
.bssktkx8m {
  d: path("M20.41 66.03c-.1-.76-.15-1.53-.15-2.32c0-10.9 8.88-19.78 19.78-19.78h53.4V61.8l27.85-22.51l-27.85-22.5v16.68h-53.4C23.36 33.47 9.8 47.04 9.8 63.71c0 3.36.56 6.68 1.68 9.89z");
}

.cmum6nbkk {
  d: path("M107.58 61.97c.09.76.16 1.53.16 2.32c0 10.9-8.87 19.77-19.77 19.77h-53.4V66.2L6.72 88.71l27.85 22.5V94.53h53.4c16.67 0 30.24-13.56 30.24-30.24c0-3.37-.57-6.69-1.69-9.89z");
}

.y94jm1b4c {
  fill: var(--svg-color--40c0e7, #40c0e7);
}

</style>
