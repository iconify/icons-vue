<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1x6nphmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-skip-next" /></template>
<style>
.c1x6nphmt {
  fill: currentColor;
  d: path("m6 18l8.5-6L6 6zm2-8.14L11.03 12L8 14.14zM16 6h2v12h-2z");
}

</style>
