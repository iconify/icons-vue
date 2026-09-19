<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-i37hbyu"/><path class="n06kg1b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-fast-rewind" /></template>
<style>
.m-i37hbyu {
  fill: currentColor;
  d: path("M9 14.14V9.86L5.97 12zm9 0V9.86L14.97 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.n06kg1b4h {
  fill: currentColor;
  d: path("m11 6l-8.5 6l8.5 6zm-2 8.14L5.97 12L9 9.86zM20 6l-8.5 6l8.5 6zm-2 8.14L14.97 12L18 9.86z");
}

</style>
