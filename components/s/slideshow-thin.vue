<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kmljfqy1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:slideshow-thin" /></template>
<style>
.kmljfqy1g {
  fill: currentColor;
  d: path("M192 52H64a12 12 0 0 0-12 12v128a12 12 0 0 0 12 12h128a12 12 0 0 0 12-12V64a12 12 0 0 0-12-12m4 140a4 4 0 0 1-4 4H64a4 4 0 0 1-4-4V64a4 4 0 0 1 4-4h128a4 4 0 0 1 4 4Zm40-136v144a4 4 0 0 1-8 0V56a4 4 0 0 1 8 0M28 56v144a4 4 0 0 1-8 0V56a4 4 0 0 1 8 0");
}

</style>
