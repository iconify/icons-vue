<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hni9v5dsm"/><path class="d92v-jc1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-perm-media" /></template>
<style>
.d92v-jc1s {
  fill: currentColor;
  d: path("M2 6H0v5h.01L0 20c0 1.1.9 2 2 2h18v-2H2zm5 9h14l-3.5-4.5l-2.5 3.01L11.5 9zM22 4h-8l-2-2H6c-1.1 0-1.99.9-1.99 2L4 16c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 12H6V4h5.17l1.41 1.41l.59.59H22z");
}

.hni9v5dsm {
  fill: currentColor;
  d: path("m13.17 6l-.59-.59L11.17 4H6v12h16V6zm4.33 4.5L21 15H7l4.5-6l3.5 4.51z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
