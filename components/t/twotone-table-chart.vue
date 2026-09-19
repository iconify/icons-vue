<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f86m4ibax"/><path class="i2f_zwb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-table-chart" /></template>
<style>
.f86m4ibax {
  fill: currentColor;
  d: path("M5 5h15v3H5zm12 5h3v9h-3zm-7 0h5v9h-5zm-5 0h3v9H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.i2f_zwb1u {
  fill: currentColor;
  d: path("M20 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h15c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2M8 19H5v-9h3zm7 0h-5v-9h5zm5 0h-3v-9h3zm0-11H5V5h15z");
}

</style>
