<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svhf6ebsk"/><path class="k9lru2b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-layers" /></template>
<style>
.k9lru2b0b {
  fill: currentColor;
  d: path("m19.37 12.8l-7.38 5.74l-7.37-5.73L3 14.07l9 7l9-7zM12 2L3 9l1.63 1.27L12 16l7.36-5.73L21 9zm0 11.47L6.26 9L12 4.53L17.74 9z");
}

.svhf6ebsk {
  fill: currentColor;
  d: path("M6.26 9L12 13.47L17.74 9L12 4.53z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
