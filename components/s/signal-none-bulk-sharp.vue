<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0w3qebum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signal-none-bulk-sharp" /></template>
<style>
.e0w3qebum {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.01 19a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2Z");
}

</style>
