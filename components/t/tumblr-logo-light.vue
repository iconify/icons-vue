<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="s64544b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tumblr-logo-light" /></template>
<style>
.s64544b5v {
  fill: currentColor;
  d: path("M192 118a6 6 0 0 0 6-6V72a6 6 0 0 0-6-6h-42V24a6 6 0 0 0-6-6h-32a6 6 0 0 0-6 6a42 42 0 0 1-42 42a6 6 0 0 0-6 6v40a6 6 0 0 0 6 6h26v58a62.07 62.07 0 0 0 62 62h40a6 6 0 0 0 6-6v-48a6 6 0 0 0-6-6h-32a10 10 0 0 1-10-10v-50Zm-32 72h26v36h-34a50.06 50.06 0 0 1-50-50v-64a6 6 0 0 0-6-6H70V77.67A54.12 54.12 0 0 0 117.67 30H138v42a6 6 0 0 0 6 6h42v28h-42a6 6 0 0 0-6 6v56a22 22 0 0 0 22 22");
}

</style>
