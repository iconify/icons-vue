<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cwsird-ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sticker-thin" /></template>
<style>
.cwsird-ds {
  fill: currentColor;
  d: path("M168 36H88a52.06 52.06 0 0 0-52 52v80a52.06 52.06 0 0 0 52 52h48a3.8 3.8 0 0 0 1.26-.21c25.46-8.48 74.05-57.07 82.53-82.53A3.8 3.8 0 0 0 220 136V88a52.06 52.06 0 0 0-52-52M44 168V88a44.05 44.05 0 0 1 44-44h80a44.05 44.05 0 0 1 44 44v44h-28a52.06 52.06 0 0 0-52 52v28H88a44.05 44.05 0 0 1-44-44m96 42v-26a44.05 44.05 0 0 1 44-44h26c-11.1 22.23-47.77 58.9-70 70");
}

</style>
