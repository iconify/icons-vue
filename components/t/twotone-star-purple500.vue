<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjg12ubaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-star-purple500" /></template>
<style>
.pjg12ubaj {
  fill: currentColor;
  d: path("m12 8.89l.94 3.11h2.82l-2.27 1.62l.93 3.01L12 14.79l-2.42 1.84l.93-3.01L8.24 12h2.82zM12 2l-2.42 8H2l6.17 4.41L5.83 22L12 17.31L18.18 22l-2.35-7.59L22 10h-7.58z");
}

</style>
