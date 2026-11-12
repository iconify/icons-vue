<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v31scrb0w"/><path class="sgn1aep-s"/><path class="ufg40xb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:spedometer-low-bold-duotone" /></template>
<style>
.sgn1aep-s {
  fill: currentColor;
  d: path("M22 12c0 5.523-4.477 10-10 10S2 17.523 2 12S6.477 2 12 2s10 4.477 10 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ufg40xb6y {
  fill: currentColor;
  d: path("M4.42 5.476q.49-.566 1.057-1.055l.053.048l1.5 1.5A.75.75 0 0 1 5.97 7.03l-1.5-1.5zM2.028 12.75a10 10 0 0 1 0-1.5H4a.75.75 0 0 1 0 1.5zm3.448 6.83a10 10 0 0 1-1.055-1.056l.049-.055l1.5-1.5a.75.75 0 0 1 1.06 1.061l-1.5 1.5zm14.104-1.056q-.49.566-1.056 1.055l-.054-.049l-1.5-1.5a.75.75 0 1 1 1.06-1.06l1.5 1.5zm2.392-7.274a10 10 0 0 1 0 1.5H20a.75.75 0 0 1 0-1.5zm-3.448-6.83q.566.49 1.055 1.056l-.049.054l-1.5 1.5a.75.75 0 1 1-1.06-1.06l1.5-1.5zM12.75 2.028V4a.75.75 0 0 1-1.5 0V2.028a10 10 0 0 1 1.5 0");
}

.v31scrb0w {
  fill: currentColor;
  d: path("M13.811 14.38a3 3 0 0 0 0-4.248a3.01 3.01 0 0 0-4.254 0c-.447.446-.76 1.373-.974 2.35c-.322 1.46-.483 2.19.1 2.772c.582.581 1.313.42 2.776.1c.978-.216 1.905-.527 2.352-.974");
}

</style>
