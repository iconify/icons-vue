<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kcr4smtlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:smiley-sticker-fill" /></template>
<style>
.kcr4smtlb {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 30.57 203.43a7.9 7.9 0 0 0 3.3-2l63.57-63.57a8 8 0 0 0 2-3.31A104.09 104.09 0 0 0 128 24M92 96a12 12 0 1 1-12 12a12 12 0 0 1 12-12m82.92 60c-10.29 17.79-27.39 28-46.92 28s-36.63-10.2-46.92-28a8 8 0 1 1 13.84-8c7.47 12.91 19.21 20 33.08 20s25.61-7.1 33.08-20a8 8 0 1 1 13.84 8M164 120a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>
