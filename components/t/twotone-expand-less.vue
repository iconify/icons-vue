<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpb10db7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-expand-less" /></template>
<style>
.bpb10db7x {
  fill: currentColor;
  d: path("m12 8l-6 6l1.41 1.41L12 10.83l4.59 4.58L18 14z");
}

</style>
