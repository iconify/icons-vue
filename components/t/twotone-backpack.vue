<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu2v3vrqi"/><path class="m6y3wntcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-backpack" /></template>
<style>
.iu2v3vrqi {
  fill: currentColor;
  d: path("M18 20H6V8c0-1.1.9-2 2-2h8c1.1 0 2 .9 2 2zM7.5 12v2h7v2h2v-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.m6y3wntcn {
  fill: currentColor;
  d: path("M17 4.14V2h-3v2h-4V2H7v2.14c-1.72.45-3 2-3 3.86v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V8c0-1.86-1.28-3.41-3-3.86M18 20H6V8c0-1.1.9-2 2-2h8c1.1 0 2 .9 2 2zM7.5 12v2h7v2h2v-4z");
}

</style>
