<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwm7ws4-s"/><path class="ii6u1sbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-insert-drive-file" /></template>
<style>
.ii6u1sbci {
  fill: currentColor;
  d: path("m20 8l-6-6H6c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2zm-2 12H6V4h7v5h5z");
}

.kwm7ws4-s {
  fill: currentColor;
  d: path("M13 4H6v16h12V9h-5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
