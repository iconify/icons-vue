<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nwsutop_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-bottom-row-20-regular" /></template>
<style>
.nwsutop_u {
  fill: currentColor;
  d: path("M14.5 3A2.5 2.5 0 0 1 17 5.5v9a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 3 14.5v-9A2.5 2.5 0 0 1 5.5 3zM4 13v1.5a1.5 1.5 0 0 0 1.356 1.493L5.5 16H7v-3zm4 3h4v-3H8zm5 0h1.5a1.5 1.5 0 0 0 1.493-1.355L16 14.5V13h-3zm3-4V5.5a1.5 1.5 0 0 0-1.355-1.493L14.5 4h-9a1.5 1.5 0 0 0-1.493 1.356L4 5.5V12z");
}

</style>
