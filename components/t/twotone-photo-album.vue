<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vut2tibcm"/><path class="a4294trox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-photo-album" /></template>
<style>
.a4294trox {
  fill: currentColor;
  d: path("M18 2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 18H6V4h5v7l2.5-1.5L16 11V4h2zm-4.38-6.5L17 18H7l2.38-3.17L11 17z");
}

.vut2tibcm {
  fill: currentColor;
  d: path("M16 4v7l-2.5-1.5L11 11V4H6v16h12V4zM7 18l2.38-3.17L11 17l2.62-3.5L17 18z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
