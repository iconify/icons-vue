<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beogc5b3h"/><path class="pljig0b1n"/><path class="wot66vb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-3k-plus" /></template>
<style>
.beogc5b3h {
  fill: currentColor;
  d: path("M5 19h14v-6.5h-1.5V14h-1v-1.5H15v-1h1.5V10h1v1.5H19V5H5zm6-10h1.5v2.25L14.25 9H16l-2.25 3L16 15h-1.75l-1.75-2.25V15H11zm-5.5 4.5h3v-1h-2v-1h2v-1h-3V9H9c.55 0 1 .45 1 1v4c0 .55-.45 1-1 1H5.5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.pljig0b1n {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 8.5h-1.5V10h-1v1.5H15v1h1.5V14h1v-1.5H19V19H5V5h14z");
}

.wot66vb_r {
  fill: currentColor;
  d: path("M10 14v-4c0-.55-.45-1-1-1H5.5v1.5h3v1h-2v1h2v1h-3V15H9c.55 0 1-.45 1-1m2.5-1.25L14.25 15H16l-2.25-3L16 9h-1.75l-1.75 2.25V9H11v6h1.5z");
}

</style>
