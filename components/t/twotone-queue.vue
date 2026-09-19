<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0ydp6tsa"/><path class="zsy-ixbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-queue" /></template>
<style>
.k0ydp6tsa {
  fill: currentColor;
  d: path("M8 16h12V4H8zm1-7h4V5h2v4h4v2h-4v4h-2v-4H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zsy-ixbxr {
  fill: currentColor;
  d: path("M2 20c0 1.1.9 2 2 2h14v-2H4V6H2zM20 2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H8V4h12zm-7-1h2v-4h4V9h-4V5h-2v4H9v2h4z");
}

</style>
