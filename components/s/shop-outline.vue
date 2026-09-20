<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1_k-op_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shop-outline" /></template>
<style>
.m1_k-op_a {
  fill: currentColor;
  d: path("m9.5 18l7-4.5l-7-4.5zM4 21q-.825 0-1.412-.587T2 19V6h6V4q0-.825.588-1.412T10 2h4q.825 0 1.413.588T16 4v2h6v13q0 .825-.587 1.413T20 21zm0-2h16V8H4zm6-13h4V4h-4zM4 19V8z");
}

</style>
