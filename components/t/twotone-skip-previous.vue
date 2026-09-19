<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6w3g-bwf"/><path class="uokof-bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-skip-previous" /></template>
<style>
.n6w3g-bwf {
  fill: currentColor;
  d: path("M16 14.14V9.86L12.97 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.uokof-bnh {
  fill: currentColor;
  d: path("M6 6h2v12H6zm12 12V6l-8.5 6zm-2-3.86L12.97 12L16 9.86z");
}

</style>
