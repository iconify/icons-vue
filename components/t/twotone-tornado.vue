<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml2oxo-eg"/><path class="f039ccs1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-tornado" /></template>
<style>
.f039ccs1z {
  fill: currentColor;
  d: path("m1 3l11 19L23 3zm11 15.01L10.26 15h3.48zM14.9 13H9.1l-1.74-3h9.27zM6.21 8L4.47 5h15.06l-1.74 3z");
}

.ml2oxo-eg {
  fill: currentColor;
  d: path("M9.1 13h5.8l1.74-3H7.36zm2.9 5.01L13.74 15h-3.48zM4.47 5l1.74 3h11.58l1.74-3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
