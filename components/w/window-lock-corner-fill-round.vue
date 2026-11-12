<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_d_w9c6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-lock-corner-fill-round" /></template>
<style>
.c_d_w9c6l {
  fill: currentColor;
  d: path("M21 9H4v7a3 3 0 0 0 3 3h1a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h10c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 22 8a1 1 0 0 1-1 1m1 9v1a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3v-1c0-1.27.803-2.405 2-2.829V15a3 3 0 1 1 6 0v.171A3 3 0 0 1 22 18m-6-3h2a1 1 0 0 0-2 0m-2 3v1a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1");
}

</style>
