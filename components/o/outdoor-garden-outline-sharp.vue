<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkj0x3n8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:outdoor-garden-outline-sharp" /></template>
<style>
.zkj0x3n8r {
  fill: currentColor;
  d: path("M2 21V6l4-3l3 2.25L12 3l3 2.25L18 3l4 3v15zm2-2h4V7L6 5.5L4 7zm6 0h4V7l-2-1.5L10 7zm6 0h4V7l-2-1.5L16 7z");
}

</style>
