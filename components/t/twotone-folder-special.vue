<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cha77qbga"/><path class="khtl98bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-folder-special" /></template>
<style>
.cha77qbga {
  fill: currentColor;
  d: path("m11.17 8l-2-2H4v12h16V8zM15 9l1.19 2.79l3.03.26l-2.3 1.99l.69 2.96L15 15.47L12.39 17l.69-2.96l-2.3-1.99l3.03-.26z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.khtl98bqi {
  fill: currentColor;
  d: path("M20 6h-8l-2-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2m0 12H4V6h5.17l2 2H20zm-6.92-3.96L12.39 17L15 15.47L17.61 17l-.69-2.96l2.3-1.99l-3.03-.26L15 9l-1.19 2.79l-3.03.26z");
}

</style>
