<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kid_hacwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:spotify-logo-light" /></template>
<style>
.kid_hacwd {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m0 192a90 90 0 1 1 90-90a90.1 90.1 0 0 1-90 90m29.31-49.2a6 6 0 0 1-8.11 2.51a44.75 44.75 0 0 0-42.4 0a6 6 0 1 1-5.6-10.62a57.37 57.37 0 0 1 53.6 0a6 6 0 0 1 2.51 8.11m32-56a6 6 0 0 1-8.12 2.46a112.67 112.67 0 0 0-106.34 0a6 6 0 1 1-5.66-10.58a124.65 124.65 0 0 1 117.66 0a6 6 0 0 1 2.44 8.14Zm-16 28A6 6 0 0 1 168 144a6.1 6.1 0 0 1-2.82-.7a79 79 0 0 0-74.36 0a6 6 0 1 1-5.64-10.6a91 91 0 0 1 85.64 0a6 6 0 0 1 2.48 8.12Z");
}

</style>
