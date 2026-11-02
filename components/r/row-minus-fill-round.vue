<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4-pn4mrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:row-minus-fill-round" /></template>
<style>
.z4-pn4mrt {
  fill: currentColor;
  d: path("M7 3h10a4 4 0 0 1 0 8H7a4 4 0 0 1 0-8m8 13a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

</style>
