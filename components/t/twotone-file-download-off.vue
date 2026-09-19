<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzyc5cslt"/><path class="jn_mx8b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-file-download-off" /></template>
<style>
.jn_mx8b4u {
  fill: currentColor;
  d: path("m11 8.17l-2-2V3h6v6h4l-3.59 3.59L13 10.17V5h-2zm10.19 13.02L2.81 2.81L1.39 4.22L6.17 9H5l7 7l.59-.59L15.17 18H5v2h12.17l2.61 2.61z");
}

.uzyc5cslt {
  fill: currentColor;
  d: path("M13 5h-2v3.17l2 2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
