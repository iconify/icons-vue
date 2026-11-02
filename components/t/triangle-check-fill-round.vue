<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0895sbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-check-fill-round" /></template>
<style>
.t0895sbyl {
  fill: currentColor;
  d: path("m15.84 5.153l5.5 9A4.5 4.5 0 0 1 17.5 21h-11a4.5 4.5 0 0 1-3.84-6.847l5.5-9a4.502 4.502 0 0 1 7.68 0m-4.948 9.325l-1.185-1.185a.999.999 0 1 0-1.414 1.414l2 2A.998.998 0 0 0 11.8 16.6l3-4a1 1 0 0 0-1.6-1.2Z");
}

</style>
