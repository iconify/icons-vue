<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rktm7jsrq"/><path class="ppw8gabdy"/><path class="j16yq48xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-drive-file-move" /></template>
<style>
.j16yq48xr {
  fill: currentColor;
  d: path("M10.59 7.41L9.17 6H4v12h16V8h-8.83zM12 9l4 4l-4 4v-3H8v-2h4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ppw8gabdy {
  fill: currentColor;
  d: path("M8 14h4v3l4-4l-4-4v3H8z");
}

.rktm7jsrq {
  fill: currentColor;
  d: path("M20 6h-8l-2-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2m0 12H4V6h5.17l1.41 1.41l.59.59H20z");
}

</style>
