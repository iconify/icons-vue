<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qt5fsub1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:television-light" /></template>
<style>
.qt5fsub1g {
  fill: currentColor;
  d: path("M216 66h-73.52l37.76-37.76a6 6 0 0 0-8.48-8.48L128 63.51L84.24 19.76a6 6 0 1 0-8.48 8.48L113.52 66H40a14 14 0 0 0-14 14v120a14 14 0 0 0 14 14h176a14 14 0 0 0 14-14V80a14 14 0 0 0-14-14M38 200V80a2 2 0 0 1 2-2h106v124H40a2 2 0 0 1-2-2m180 0a2 2 0 0 1-2 2h-58V78h58a2 2 0 0 1 2 2Zm-20-84a10 10 0 1 1-10-10a10 10 0 0 1 10 10m0 48a10 10 0 1 1-10-10a10 10 0 0 1 10 10");
}

</style>
