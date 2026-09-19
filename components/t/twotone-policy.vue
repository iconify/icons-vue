<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv44t_bvu"/><path class="gsq3_ccad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-policy" /></template>
<style>
.gsq3_ccad {
  fill: currentColor;
  d: path("M12 1L3 5v6c0 5.55 3.84 10.74 9 12c.65-.16 1.27-.38 1.87-.65c1.8-.82 3.36-2.13 4.57-3.74C20.04 16.46 21 13.77 21 11V5zm7 10c0 1.85-.51 3.65-1.38 5.21l-1.45-1.45a4.994 4.994 0 0 0-.64-6.29a5.003 5.003 0 0 0-7.07 0a5.003 5.003 0 0 0 0 7.07a5.006 5.006 0 0 0 6.29.64l1.72 1.72c-1.19 1.42-2.73 2.51-4.47 3.04c-4.02-1.25-7-5.42-7-9.94V6.3l7-3.11l7 3.11zm-4 1c0 1.66-1.34 3-3 3s-3-1.34-3-3s1.34-3 3-3s3 1.34 3 3");
}

.wv44t_bvu {
  fill: currentColor;
  d: path("M5 6.3V11c0 4.52 2.98 8.69 7 9.93c1.74-.53 3.28-1.62 4.47-3.04l-1.72-1.72a4.994 4.994 0 0 1-6.29-.64a5.003 5.003 0 0 1 0-7.07a5.003 5.003 0 0 1 7.07 0a5.006 5.006 0 0 1 .64 6.29l1.45 1.45C18.49 14.65 19 12.85 19 11V6.3l-7-3.11z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
