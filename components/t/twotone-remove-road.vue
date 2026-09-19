<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iszcfc_ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-remove-road" /></template>
<style>
.iszcfc_ec {
  fill: currentColor;
  d: path("M18 4h2v9h-2zM4 4h2v16H4zm7 0h2v4h-2zm0 6h2v4h-2zm0 6h2v4h-2zm11.5.41L21.09 15L19 17.09L16.91 15l-1.41 1.41l2.09 2.09l-2.09 2.09L16.91 22L19 19.91L21.09 22l1.41-1.41l-2.09-2.09z");
}

</style>
