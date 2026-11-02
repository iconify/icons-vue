<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwr2qro4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-taurus-fill" /></template>
<style>
.uwr2qro4d {
  fill: currentColor;
  d: path("M11.983 8h.035A4.995 4.995 0 0 0 17 3a1 1 0 0 1 2 0a6.97 6.97 0 0 1-2.05 4.95A7 7 0 0 1 15.609 9A7.002 7.002 0 0 1 12 22A7.001 7.001 0 0 1 8.391 9A7 7 0 0 1 7.05 7.95A6.97 6.97 0 0 1 5 3a1.002 1.002 0 0 1 1.556-.831A1 1 0 0 1 7 3a4.994 4.994 0 0 0 4.983 5M12 10h-.017a5 5 0 1 0 .035 0Z");
}

</style>
