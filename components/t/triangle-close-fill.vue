<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do8d__b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-close-fill" /></template>
<style>
.do8d__b6f {
  fill: currentColor;
  d: path("m14.591 4.488l7 12A2.999 2.999 0 0 1 19 21H5a2.999 2.999 0 0 1-2.591-4.512l7-12a3 3 0 0 1 5.182 0m-3.884 6.805a.999.999 0 1 0-1.414 1.414L10.586 14l-1.293 1.293a.999.999 0 1 0 1.414 1.414L12 15.414l1.293 1.293a.999.999 0 1 0 1.414-1.414L13.414 14l1.293-1.293a.999.999 0 1 0-1.414-1.414L12 12.586Z");
}

</style>
