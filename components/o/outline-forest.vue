<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkqwyvbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-forest" /></template>
<style>
.xkqwyvbyb {
  fill: currentColor;
  d: path("m24 18l-3.86-6H22L15 2l-3 4.29L9 2L2 12h1.86L0 18h7v4h4v-4h2v4h4v-4zM15 5.49L18.16 10h-1.68l3.86 6h-3.62l-2.57-4H16l-2.78-3.97zM3.66 16l3.86-6H5.84L9 5.49L12.16 10h-1.68l3.86 6z");
}

</style>
