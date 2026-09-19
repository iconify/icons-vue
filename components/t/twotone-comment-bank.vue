<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1rjrkbkb"/><path class="xr4yj7fak"/><path class="z2l0rtbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-comment-bank" /></template>
<style>
.f1rjrkbkb {
  fill: currentColor;
  d: path("m4 18l2-2h14V4H4zm9-12h5v8l-2.5-1.5L13 14z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xr4yj7fak {
  fill: currentColor;
  d: path("M18 14V6h-5v8l2.5-1.5z");
}

.z2l0rtbum {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v18l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H6l-2 2V4h16z");
}

</style>
