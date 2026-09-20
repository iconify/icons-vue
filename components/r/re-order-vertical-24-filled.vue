<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1edizbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-vertical-24-filled" /></template>
<style>
.g1edizbwy {
  fill: currentColor;
  d: path("M13 21V3a1 1 0 0 1 1.993-.117L15 3v18a1 1 0 0 1-1.993.117zm-4 0V3a1 1 0 0 1 1.993-.117L11 3v18a1 1 0 0 1-1.993.117z");
}

</style>
