<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w1k9p680v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:right-arrow-curving-down" /></template>
<style>
.w1k9p680v {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M46.68 21.56L36.22 40.88c3.2 0 7.74 1.1 10.46 2.88c4.89 3.2 7.2 8.67 7.2 14V67.8H25.91l38.11 38.64L102.1 67.8H74.15v-9.96c0-28.02-19.63-34.74-27.47-36.28");
}

</style>
