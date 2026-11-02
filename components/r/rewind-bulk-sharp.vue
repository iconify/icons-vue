<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po40rbvpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rewind-bulk-sharp" /></template>
<style>
.po40rbvpr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.514 6.126A1 1 0 0 1 13 7v3.3l7.514-4.174A1 1 0 0 1 22 7v10a1 1 0 0 1-1.486.874L13 13.7V17a1 1 0 0 1-1.486.874l-9-5a1 1 0 0 1 0-1.748Z");
}

</style>
