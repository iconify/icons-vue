<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l9g2p6b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:virus-light" /></template>
<style>
.l9g2p6b0g {
  fill: currentColor;
  d: path("M134 108a26 26 0 1 0-26 26a26 26 0 0 0 26-26m-26 14a14 14 0 1 1 14-14a14 14 0 0 1-14 14m82 6a14 14 0 1 1-14-14a14 14 0 0 1 14 14m-48 48a14 14 0 1 1-14-14a14 14 0 0 1 14 14m98-54h-18.2a93.57 93.57 0 0 0-23.26-56.06l13.7-13.7a6 6 0 0 0-8.48-8.48l-13.7 13.7A93.57 93.57 0 0 0 134 34.2V16a6 6 0 0 0-12 0v18.2a93.57 93.57 0 0 0-56.06 23.26l-13.7-13.7a6 6 0 0 0-8.48 8.48l13.7 13.7A93.57 93.57 0 0 0 34.2 122H16a6 6 0 0 0 0 12h18.2a93.57 93.57 0 0 0 23.26 56.06l-13.7 13.7a6 6 0 1 0 8.48 8.48l13.7-13.7A93.57 93.57 0 0 0 122 221.8V240a6 6 0 0 0 12 0v-18.2a93.57 93.57 0 0 0 56.06-23.26l13.7 13.7a6 6 0 0 0 8.48-8.48l-13.7-13.7A93.57 93.57 0 0 0 221.8 134H240a6 6 0 0 0 0-12m-112 88a82 82 0 1 1 82-82a82.1 82.1 0 0 1-82 82");
}

</style>
