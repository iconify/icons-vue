<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va01w2blk"/><path class="e76zxsbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-nest-cam-wired-stand" /></template>
<style>
.e76zxsbkk {
  fill: currentColor;
  d: path("M16 1c-.15 0 .11-.02-4.28.42C8.47 1.75 6 4.48 6 7.75s2.47 6 5.72 6.33l1.9.19l-.56.85c-.35-.08-.7-.12-1.06-.12c-2.76 0-5 2.24-5 5v2c0 .55.45 1 1 1h8c.55 0 1-.45 1-1v-2c0-1.67-.83-3.15-2.09-4.06l.97-1.45c.04 0 .09.01.13.01c1.09 0 2-.89 2-2V3C18 1.89 17.09 1 16 1m-1 19v1H9v-1c0-1.65 1.35-3 3-3s3 1.35 3 3m-3.08-7.91C9.69 11.86 8 10 8 7.75s1.69-4.11 3.92-4.34L16 3l.03 9.5z");
}

.va01w2blk {
  fill: currentColor;
  d: path("M12 17c-1.65 0-3 1.35-3 3v1h6v-1c0-1.65-1.35-3-3-3m4-14l-4.08.41C9.69 3.64 8 5.5 8 7.75s1.69 4.11 3.92 4.34l4.11.42z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
