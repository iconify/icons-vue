<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r32_lknzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-system-update-alt" /></template>
<style>
.r32_lknzh {
  fill: currentColor;
  d: path("m12 16l4-4h-3V3h-2v9H8zm9-13h-6v1.99h6v14.03H3V4.99h6V3H3c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2");
}

</style>
