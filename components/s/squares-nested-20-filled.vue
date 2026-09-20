<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p7qwflbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:squares-nested-20-filled" /></template>
<style>
.p7qwflbht {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v1.764A3 3 0 0 0 15 7h-5a3 3 0 0 0-3 3v5c0 .768.289 1.47.764 2H6a3 3 0 0 1-3-3zm7 11h4a3 3 0 0 0 3-3v-4a2 2 0 0 0-2-2h-5a2 2 0 0 0-2 2v5a2 2 0 0 0 2 2");
}

</style>
