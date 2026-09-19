<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdra9y4sb"/><path class="fq_zazowq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-nightlight" /></template>
<style>
.fq_zazowq {
  fill: currentColor;
  d: path("M14 12c0-3.7 2.01-6.92 5-8.65A10 10 0 0 0 14 2C8.48 2 4 6.48 4 12s4.48 10 10 10c1.82 0 3.53-.5 5-1.35c-2.99-1.73-5-4.95-5-8.65m1.01 7.93c-.33.05-.67.07-1.01.07c-4.41 0-8-3.59-8-8s3.59-8 8-8c.34 0 .68.02 1.01.07C13.1 6.23 12 9.05 12 12s1.1 5.77 3.01 7.93");
}

.mdra9y4sb {
  fill: currentColor;
  d: path("M6 12c0-4.41 3.59-8 8-8c.34 0 .68.02 1.01.07C13.1 6.23 12 9.05 12 12s1.1 5.77 3.01 7.93c-.33.05-.67.07-1.01.07c-4.41 0-8-3.59-8-8");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
