<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq33o9bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-insert-invitation" /></template>
<style>
.oq33o9bjz {
  fill: currentColor;
  d: path("M17 12h-5v5h5zM16 1v2H8V1H6v2H3.01v18H21V3h-3V1zm3 18H5V8h14z");
}

</style>
