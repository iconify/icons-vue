<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6ffx_e3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:standing-desk-fill" /></template>
<style>
.k6ffx_e3o {
  fill: currentColor;
  d: path("M4.293 3.293a1 1 0 0 1 1.414 0l2 2a.999.999 0 1 1-1.414 1.414L5 5.414L3.707 6.707a.999.999 0 1 1-1.414-1.414ZM13 3h6a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3h-2v2h2a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0v-2a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1v2a1 1 0 0 1-2 0v-2a3 3 0 0 1 3-3h10v-2h-2a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m-8 7.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414Z");
}

</style>
