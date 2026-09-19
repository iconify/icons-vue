<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aack33bya"/><path class="qg2_i7bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-chat" /></template>
<style>
.aack33bya {
  fill: currentColor;
  d: path("M20 4H4v13.17L5.17 16H20zm-6 10H6v-2h8zm4-3H6V9h12zm0-3H6V6h12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qg2_i7bec {
  fill: currentColor;
  d: path("M20 18c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2H4c-1.1 0-1.99.9-1.99 2L2 22l4-4zm-16-.83V4h16v12H5.17zM6 12h8v2H6zm0-3h12v2H6zm0-3h12v2H6z");
}

</style>
