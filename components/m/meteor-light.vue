<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r0gj1q-ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:meteor-light" /></template>
<style>
.r0gj1q-ml {
  fill: currentColor;
  d: path("M96 122a38 38 0 1 0 38 38a38 38 0 0 0-38-38m0 64a26 26 0 1 1 26-26a26 26 0 0 1-26 26m124.24-62.24a6 6 0 0 1 0 8.48l-48 48a6 6 0 0 1-8.48-8.48l48-48a6 6 0 0 1 8.48 0m-56 8.48a6 6 0 0 1-8.48-8.48l24-24a6 6 0 0 1 8.48 8.48Zm64-64l-16 16a6 6 0 0 1-8.48-8.48l16-16a6 6 0 0 1 8.48 8.48M123.76 91.76l72-72a6 6 0 0 1 8.48 8.48l-72 72a6 6 0 1 1-8.48-8.48M145.5 201a6 6 0 0 1 0 8.49a70 70 0 0 1-99-99l82.75-82.74a6 6 0 1 1 8.48 8.48L55 119a58 58 0 1 0 82 82a6 6 0 0 1 8.5 0");
}

</style>
