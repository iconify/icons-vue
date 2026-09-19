<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r1bq7qb_u"/><circle class="ndaauacgs"/><circle class="mydpzzbnu"/><path class="lp4dazc7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:upside-down-face" /></template>
<style>
.lp4dazc7s {
  fill: currentColor;
  d: path("M45.771 22.143c-2.457-4.047-7.417-7.65-13.771-7.65s-11.313 3.604-13.771 7.65c-.658 1.083.217 2.255 1.187 1.578c8.11-5.656 17.106-5.623 25.168 0c.97.676 1.845-.495 1.187-1.578");
}

.mydpzzbnu {
  cx: 20.5px;
  cy: 37.408px;
  r: 5px;
  fill: currentColor;
}

.ndaauacgs {
  cx: 43.5px;
  cy: 37.408px;
  r: 5px;
  fill: currentColor;
}

.r1bq7qb_u {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 57.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5S59.5 16.836 59.5 32S47.163 59.5 32 59.5");
}

</style>
