<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhb92-bvg"/><path class="om7s9pbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-delete-forever" /></template>
<style>
.om7s9pbhq {
  fill: currentColor;
  d: path("M14.12 10.47L12 12.59l-2.13-2.12l-1.41 1.41L10.59 14l-2.12 2.12l1.41 1.41L12 15.41l2.12 2.12l1.41-1.41L13.41 14l2.12-2.12zM15.5 4l-1-1h-5l-1 1H5v2h14V4zM6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6zM8 9h8v10H8z");
}

.qhb92-bvg {
  fill: currentColor;
  d: path("M16 9H8v10h8zm-.47 7.12l-1.41 1.41L12 15.41l-2.12 2.12l-1.41-1.41L10.59 14l-2.13-2.12l1.41-1.41L12 12.59l2.12-2.12l1.41 1.41L13.41 14z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
