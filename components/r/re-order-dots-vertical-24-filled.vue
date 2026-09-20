<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe-6x4qdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-dots-vertical-24-filled" /></template>
<style>
.fe-6x4qdh {
  fill: currentColor;
  d: path("M16 17a2 2 0 1 1 0 4a2 2 0 0 1 0-4m-8 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8-7a2 2 0 1 1 0 4a2 2 0 0 1 0-4m-8 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8-7a2 2 0 1 1 0 4a2 2 0 0 1 0-4M8 3a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>
