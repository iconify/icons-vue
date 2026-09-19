<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="w_2vieskh"/><path class="p6-c89_eg"/><path class="b4_bdzbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:pill" /></template>
<style>
.b4_bdzbhj {
  fill: var(--svg-color--16b9a8, #16b9a8);
  d: path("M47.02 26.17a3.264 3.264 0 1 1-6.527 0v-7.274a3.263 3.263 0 1 1 6.527 0z");
}

.p6-c89_eg {
  fill: var(--svg-color--04a69c, #04a69c);
  d: path("M30.728 0C20.384 0 12 8.384 12 18.728v15.608c0 1.366 8.384 2.475 18.728 2.475c10.342 0 18.727-1.108 18.727-2.475V18.728C49.454 8.384 41.069 0 30.728 0");
}

.w_2vieskh {
  fill: var(--svg-color--f7ec35, #f7ec35);
  d: path("M30.728 36.811C20.384 36.811 12 35.702 12 34.336V44.99c0 10.343 8.384 18.728 18.728 18.728c10.342 0 18.727-8.385 18.727-18.728V34.336c0 1.366-8.386 2.475-18.727 2.475");
}

</style>
