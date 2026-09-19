<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-vhzgk7v"/><path class="lr65sub2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-new-label" /></template>
<style>
.lr65sub2v {
  fill: currentColor;
  d: path("m21 12l-4.37 6.16c-.37.52-.98.84-1.63.84h-3v-2h3l3.55-5L15 7H5v3H3V7c0-1.1.9-2 2-2h10c.65 0 1.26.31 1.63.84zm-11 3H7v-3H5v3H2v2h3v3h2v-3h3z");
}

.r-vhzgk7v {
  fill: currentColor;
  d: path("M12 17v-4H9v-3H5V7h10l3.55 5L15 17z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
