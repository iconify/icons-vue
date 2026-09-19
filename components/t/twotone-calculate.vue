<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j09-nf4vt"/><path class="bn6ebpb5p"/><path class="xhi6_v41q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-calculate" /></template>
<style>
.bn6ebpb5p {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

.j09-nf4vt {
  fill: currentColor;
  d: path("M5 19h14V5H5zm8.03-11.94L14.09 6l1.41 1.41L16.91 6l1.06 1.06l-1.41 1.41l1.41 1.41l-1.06 1.06l-1.41-1.4l-1.41 1.41l-1.06-1.06l1.41-1.41zM13 13.25h5v1.5h-5zm0 2.5h5v1.5h-5zM6.25 7.72h5v1.5h-5zM6 14.5h2v-2h1.5v2h2V16h-2v2H8v-2H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xhi6_v41q {
  fill: currentColor;
  d: path("M6.25 7.72h5v1.5h-5zM13 15.75h5v1.5h-5zm0-2.5h5v1.5h-5zM8 18h1.5v-2h2v-1.5h-2v-2H8v2H6V16h2zm6.09-7.05l1.41-1.41l1.41 1.41l1.06-1.06l-1.41-1.42l1.41-1.41L16.91 6L15.5 7.41L14.09 6l-1.06 1.06l1.41 1.41l-1.41 1.42z");
}

</style>
