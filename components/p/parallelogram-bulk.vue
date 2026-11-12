<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1vekci8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:parallelogram-bulk" /></template>
<style>
.p1vekci8w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m21.976 3.217l-4 18A1 1 0 0 1 17 22H3a1.002 1.002 0 0 1-.976-1.217l4-18A1 1 0 0 1 7 2h14a1.002 1.002 0 0 1 .976 1.217");
}

</style>
