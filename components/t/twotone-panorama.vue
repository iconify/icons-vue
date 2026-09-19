<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x324m8v9t"/><path class="r93eryfmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-panorama" /></template>
<style>
.r93eryfmu {
  fill: currentColor;
  d: path("M21 4H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 14H3V6h18zm-6.5-7L11 15.51L8.5 12.5L5 17h14z");
}

.x324m8v9t {
  fill: currentColor;
  d: path("M3 18h18V6H3zm5.5-5.5l2.5 3.01L14.5 11l4.5 6H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
