<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdvr37bmi"/><path class="c8_xq8b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mic-external-off" /></template>
<style>
.c8_xq8b0r {
  fill: currentColor;
  d: path("M10 5c0-1.66-1.34-3-3-3c-.62 0-1.19.19-1.67.5l4.15 4.15C9.8 6.18 10 5.61 10 5m4 1c0-1.1.9-2 2-2s2 .9 2 2v9.17l2 2V6c0-2.21-1.79-4-4-4s-4 1.79-4 4v3.17l2 2zM2.1 2.1L.69 3.51L5.17 8H4l1 10h1c0 2.21 1.79 4 4 4s4-1.79 4-4v-1.17l6.49 6.49l1.41-1.41zM7.19 16h-.38l-.6-6h.96l.56.56zM12 18c0 1.1-.9 2-2 2s-2-.9-2-2h1l.56-5.61L12 14.83z");
}

.gdvr37bmi {
  fill: currentColor;
  d: path("m6.21 10l.6 6h.38l.54-5.44l-.56-.56z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
