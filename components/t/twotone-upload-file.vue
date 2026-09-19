<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6iysvbhh"/><path class="mc63i8bvn"/><path class="p2ywtxdnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-upload-file" /></template>
<style>
.mc63i8bvn {
  fill: currentColor;
  d: path("M14 2H6c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8zm4 18H6V4h7v5h5z");
}

.p2ywtxdnu {
  fill: currentColor;
  d: path("M8 15h3v4h2v-4h3l-3.99-4z");
}

.p6iysvbhh {
  fill: currentColor;
  d: path("M13 4H6v16h12V9h-5zm3 11h-3v4h-2v-4H8l4.01-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
