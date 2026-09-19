<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvn00-b9s"/><path class="m5unsyqjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-announcement" /></template>
<style>
.m5unsyqjw {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v18l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H5.17l-.59.59l-.58.58V4h16zM11 5h2v6h-2zm0 8h2v2h-2z");
}

.zvn00-b9s {
  fill: currentColor;
  d: path("M4 4v13.17l.59-.59l.58-.58H20V4zm9 11h-2v-2h2zm0-4h-2V5h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
