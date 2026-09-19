<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1q_3tb2w"/><path class="frkbr5ois"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-token" /></template>
<style>
.a1q_3tb2w {
  fill: currentColor;
  d: path("m12 4.29l5.91 3.28l-3.01 1.67C14.17 8.48 13.14 8 12 8s-2.17.48-2.9 1.24L6.09 7.57zm-1 14.87l-6-3.33V9.26L8.13 11c-.09.31-.13.65-.13 1c0 1.86 1.27 3.43 3 3.87zM10 12c0-1.1.9-2 2-2s2 .9 2 2s-.9 2-2 2s-2-.9-2-2m3 7.16v-3.28c1.73-.44 3-2.01 3-3.87c0-.35-.04-.69-.13-1.01L19 9.26v6.57z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.frkbr5ois {
  fill: currentColor;
  d: path("m21 7l-9-5l-9 5v10l9 5l9-5zm-9-2.71l5.91 3.28l-3.01 1.67C14.17 8.48 13.14 8 12 8s-2.17.48-2.9 1.24L6.09 7.57zm-1 14.87l-6-3.33V9.26L8.13 11c-.09.31-.13.65-.13 1c0 1.86 1.27 3.43 3 3.87zM10 12c0-1.1.9-2 2-2s2 .9 2 2s-.9 2-2 2s-2-.9-2-2m3 7.16v-3.28c1.73-.44 3-2.01 3-3.87c0-.35-.04-.69-.13-1.01L19 9.26v6.57z");
}

</style>
