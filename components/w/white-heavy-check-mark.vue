<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ibeu40b2r"/><path class="s2ai-zw7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:white-heavy-check-mark" /></template>
<style>
.ibeu40b2r {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  stroke: var(--svg-color--e0e0e0, #e0e0e0);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--6px, 6px);
  d: path("M48.3 102.32L12.65 66.87a2.2 2.2 0 0 1 0-3.12l9-9.01c.86-.86 2.25-.86 3.11 0l23.47 23.33c.86.86 2.26.85 3.12-.01l51.86-52.36c.86-.87 2.26-.87 3.13-.01l9.01 9.01c.86.86.86 2.25.01 3.11l-56.5 57.01l.01.01l-7.45 7.49c-.86.86-2.26.86-3.12 0z");
}

.s2ai-zw7s {
  fill: var(--svg-color--757f3f, #757f3f);
  d: path("M-27.53-17.19c-3.08-3.09-8.13-3.08-11.21 0L-63.65 7.72c-3.08 3.08-8.13 3.08-11.21 0l-24.91-24.9c-3.08-3.08-8.12-3.08-11.21 0l-6.21 6.21c-3.08 3.09-3.08 8.13 0 11.21l24.91 24.91c3.08 3.08 3.08 8.13 0 11.21l-24.91 24.91c-3.08 3.08-3.08 8.12 0 11.21l6.22 6.22c3.08 3.08 8.13 3.08 11.21 0l24.91-24.91c3.08-3.08 8.13-3.08 11.21 0l24.91 24.91c3.08 3.08 8.13 3.08 11.21 0l6.21-6.22c3.08-3.09 3.08-8.13 0-11.21l-24.91-24.9c-3.08-3.08-3.08-8.13 0-11.21L-21.31.25c3.08-3.08 3.08-8.12 0-11.21z");
}

</style>
