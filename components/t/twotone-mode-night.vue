<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw7hvaczg"/><path class="pobimaclk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mode-night" /></template>
<style>
.pobimaclk {
  fill: currentColor;
  d: path("M9.5 2c-1.82 0-3.53.5-5 1.35c2.99 1.73 5 4.95 5 8.65s-2.01 6.92-5 8.65c1.47.85 3.18 1.35 5 1.35c5.52 0 10-4.48 10-10S15.02 2 9.5 2m0 18c-.34 0-.68-.02-1.01-.07c1.91-2.16 3.01-4.98 3.01-7.93s-1.1-5.77-3.01-7.93C8.82 4.02 9.16 4 9.5 4c4.41 0 8 3.59 8 8s-3.59 8-8 8");
}

.rw7hvaczg {
  fill: currentColor;
  d: path("M9.5 4c-.34 0-.68.02-1.01.07C10.4 6.23 11.5 9.05 11.5 12s-1.1 5.77-3.01 7.93c.33.05.67.07 1.01.07c4.41 0 8-3.59 8-8s-3.59-8-8-8");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
