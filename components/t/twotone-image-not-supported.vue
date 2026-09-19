<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y83dh26wx"/><path class="u1cmzubrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-image-not-supported" /></template>
<style>
.u1cmzubrq {
  fill: currentColor;
  d: path("M5.83 3H19c1.1 0 2 .9 2 2v13.17l-2-2V5H7.83zm14.66 20.31L18.17 21H5c-1.1 0-2-.9-2-2V5.83L.69 3.51L2.1 2.1l1.49 1.49L5 5l8.11 8.11l2.69 2.69L19 19l1.41 1.41l1.49 1.49zM16.17 19l-2-2H6l3-4l2 2.72l.84-1.05L5 7.83V19z");
}

.y83dh26wx {
  fill: currentColor;
  d: path("M7.83 5H19v11.17zm8.34 14l-2-2H6l3-4l2 2.72l.84-1.05L5 7.83V19z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
