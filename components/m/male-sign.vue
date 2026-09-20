<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r9rioofmx"/><path class="v914n36ko"/><path class="hx2d66fyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:male-sign" /></template>
<style>
.hx2d66fyy {
  fill: var(--svg-color--fff, #fff);
  d: path("M28.5 7h-8.969a1.5 1.5 0 1 0 0 3h5.348l-7 6.879L20 19l7-6.879V17.5a1.5 1.5 0 0 0 3 0v-9A1.5 1.5 0 0 0 28.5 7");
}

.r9rioofmx {
  fill: var(--svg-color--269, #269);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.v914n36ko {
  fill: var(--svg-color--fff, #fff);
  d: path("M15 30.5c-4.687 0-8.5-3.813-8.5-8.5s3.813-8.5 8.5-8.5s8.5 3.813 8.5 8.5s-3.813 8.5-8.5 8.5m0-14c-3.032 0-5.5 2.468-5.5 5.5s2.468 5.5 5.5 5.5s5.5-2.468 5.5-5.5s-2.468-5.5-5.5-5.5");
}

</style>
