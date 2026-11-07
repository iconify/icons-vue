<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym2nw8bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:packages-fill" /></template>
<style>
.ym2nw8bli {
  fill: currentColor;
  d: path("m17.5 10.257l3.394 1.697A2 2 0 0 1 22 13.743v4.389a2 2 0 0 1-1.106 1.789l-3.5 1.75a2 2 0 0 1-1.788 0L12 19.868l-3.606 1.803a2 2 0 0 1-1.788 0l-3.5-1.75A2 2 0 0 1 2 18.132v-4.389a2 2 0 0 1 1.106-1.789L6.5 10.257V5.868a2 2 0 0 1 1.106-1.789l3.5-1.75a2 2 0 0 1 1.788 0l3.5 1.75A2 2 0 0 1 17.5 5.868ZM12 4.118L9.736 5.25L12 6.382l2.264-1.132Zm3.5 2.75L13 8.118v3.389l2.5-1.25ZM5.236 13.125L7.5 14.257l2.264-1.132L7.5 11.993ZM16.5 11.993l-2.264 1.132l2.264 1.132l2.264-1.132Zm-5.5 2.75l-2.5 1.25v3.389l2.5-1.25Zm9 3.389v-3.389l-2.5 1.25v3.389Z");
}

</style>
