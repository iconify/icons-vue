<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tku3drzoh"/><path class="gtqi5iynl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-offline-pin" /></template>
<style>
.gtqi5iynl {
  fill: currentColor;
  d: path("M12 2C6.5 2 2 6.5 2 12s4.5 10 10 10s10-4.5 10-10S17.5 2 12 2m0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8s8 3.59 8 8s-3.59 8-8 8m-5-5h10v2H7zm3.3-3.8L8.4 9.3L7 10.7l3.3 3.3L17 7.3l-1.4-1.4z");
}

.tku3drzoh {
  fill: currentColor;
  d: path("M12 4c-4.41 0-8 3.59-8 8s3.59 8 8 8s8-3.59 8-8s-3.59-8-8-8m5 13H7v-2h10zm-6.7-3L7 10.7l1.4-1.4l1.9 1.9l5.3-5.3L17 7.3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
