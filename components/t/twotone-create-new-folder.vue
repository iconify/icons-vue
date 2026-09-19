<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp21gtz-k"/><path class="oh0wq9p7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-create-new-folder" /></template>
<style>
.mp21gtz-k {
  fill: currentColor;
  d: path("m11.17 8l-.59-.59L9.17 6H4v12h16V8zM14 10h2v2h2v2h-2v2h-2v-2h-2v-2h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.oh0wq9p7e {
  fill: currentColor;
  d: path("M20 6h-8l-2-2H4c-1.11 0-1.99.89-1.99 2L2 18c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V8c0-1.11-.89-2-2-2m0 12H4V6h5.17l1.41 1.41l.59.59H20zm-8-4h2v2h2v-2h2v-2h-2v-2h-2v2h-2z");
}

</style>
