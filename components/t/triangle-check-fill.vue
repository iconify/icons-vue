<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-xscobyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-check-fill" /></template>
<style>
.g-xscobyq {
  fill: currentColor;
  d: path("m14.591 4.488l7 12A2.999 2.999 0 0 1 19 21H5a2.999 2.999 0 0 1-2.591-4.512l7-12a3 3 0 0 1 5.182 0m-3.699 9.99l-1.185-1.185a.999.999 0 1 0-1.414 1.414l2 2A.998.998 0 0 0 11.8 16.6l3-4a1 1 0 0 0-1.6-1.2Z");
}

</style>
