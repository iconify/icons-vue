<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1ascybjk"/><path class="docibcbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-fast-forward" /></template>
<style>
.docibcbci {
  fill: currentColor;
  d: path("m4 18l8.5-6L4 6zm2-8.14L9.03 12L6 14.14zM21.5 12L13 6v12zM15 9.86L18.03 12L15 14.14z");
}

.t1ascybjk {
  fill: currentColor;
  d: path("M15 9.86v4.28L18.03 12zm-9 0v4.28L9.03 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
