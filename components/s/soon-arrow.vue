<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xq8jkzbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:soon-arrow" /></template>
<style>
.xq8jkzbkg {
  fill: var(--svg-color--4d5357, #4d5357);
  d: path("M61 18L45 2v10H3v12h42v10zM8 62c-3.3 0-6-2.8-6-6.3h3c0 1.6 1.3 3 3 3s3-1.3 3-3s-1.3-3-3-3c-3.3 0-6-2.8-6-6.3C2 42.8 4.7 40 8 40s6 2.8 6 6.3h-3c0-1.6-1.3-3-3-3s-3 1.3-3 3s1.3 3 3 3c3.3 0 6 2.8 6 6.3c0 3.6-2.7 6.4-6 6.4m16 0c-3.3 0-6-2.8-6-6.3v-9.3c0-3.5 2.7-6.3 6-6.3s6 2.8 6 6.3v9.3c0 3.5-2.7 6.3-6 6.3m0-18.6c-1.7 0-3 1.3-3 3v9.3c0 1.6 1.3 3 3 3s3-1.3 3-3v-9.3c0-1.7-1.3-3-3-3M40 62c-3.3 0-6-2.8-6-6.3v-9.3c0-3.5 2.7-6.3 6-6.3s6 2.8 6 6.3v9.3c0 3.5-2.7 6.3-6 6.3m0-18.6c-1.7 0-3 1.3-3 3v9.3c0 1.6 1.3 3 3 3s3-1.3 3-3v-9.3c0-1.7-1.3-3-3-3m13 4.3L58.8 62H62V40h-3v14.3L53.2 40H50v22h3z");
}

</style>
