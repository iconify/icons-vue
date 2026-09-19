<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tbhi7z_zm"/><path class="zssxsgbbe"/><path class="wvhcllb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:spoon" /></template>
<style>
.tbhi7z_zm {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M41.9 38.4L31.5 28c-3.1-3.1-.4-11-8.6-19.2C17.1 3 7.6-.2 3.7 3.7S3 17.1 8.8 22.9c8.2 8.2 16 5.5 19.2 8.6l10.4 10.4c4.3 4.3 4.6 5.8 11.3 14.8c3.3 4.5 6.5 7.3 10.4 3.4c4-4 1.1-7.1-3.4-10.4c-9-6.7-10.4-7-14.8-11.3");
}

.wvhcllb0z {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M13.2 23.7C6.3 16.8 4 7.9 7.7 3.3c-1.3.1-2.3.5-3.1 1.3C1.5 7.7 4 16.3 9.7 22c2.3 2.3 4.6 3.7 6.7 4.6c0 0 0-.1-.1-.1c-1.1-.8-2.1-1.8-3.1-2.8");
}

.zssxsgbbe {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.6 5.9C21 12.8 22.8 20.8 20 26c.2 0 .4.1.5.1c1.9 0 3.6-.5 4.8-1.7s2-2.9 1.7-4.8c-.4-2.8-1.9-6-5.2-9.3c-1.8-1.9-4-3.4-6.2-4.4");
}

</style>
