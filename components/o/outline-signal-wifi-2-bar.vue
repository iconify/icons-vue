<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogp381bbc"/><path class="oiy13ij0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-signal-wifi-2-bar" /></template>
<style>
.ogp381bbc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M23.64 7c-.45-.34-4.93-4-11.64-4C5.28 3 .81 6.66.36 7L12 21.5z");
}

.oiy13ij0f {
  fill: currentColor;
  d: path("M4.79 12.52L12 21.5l7.21-8.99C18.85 12.24 16.1 10 12 10s-6.85 2.24-7.21 2.52");
}

</style>
