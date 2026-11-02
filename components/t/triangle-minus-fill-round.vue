<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdm-kab9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-minus-fill-round" /></template>
<style>
.wdm-kab9m {
  fill: currentColor;
  d: path("m15.84 5.153l5.5 9A4.5 4.5 0 0 1 17.5 21h-11a4.5 4.5 0 0 1-3.84-6.847l5.5-9a4.502 4.502 0 0 1 7.68 0M14 13h-4a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2");
}

</style>
