<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5stc7bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-minus-fill-sharp" /></template>
<style>
.c5stc7bfc {
  fill: currentColor;
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m14-10H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2");
}

</style>
