<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7eevwb_f"/><path class="tt0wdpbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-live-tv" /></template>
<style>
.tt0wdpbjz {
  fill: currentColor;
  d: path("M9 10v8l7-4zm12-4h-7.58l3.29-3.29L16 2l-4 4h-.03l-4-4l-.69.71L10.56 6H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2m0 14H3V8h18z");
}

.y7eevwb_f {
  fill: currentColor;
  d: path("M3 20h18V8H3zm6-10l7 4l-7 4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
