<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kr2u8lbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-four-fill" /></template>
<style>
.kr2u8lbxf {
  fill: currentColor;
  d: path("M104.65 144L144 94.81V144ZM216 40v176a16 16 0 0 1-16 16H56a16 16 0 0 1-16-16V40a16 16 0 0 1 16-16h144a16 16 0 0 1 16 16m-32 112a8 8 0 0 0-8-8h-16V72a8 8 0 0 0-14.25-5l-64 80A8 8 0 0 0 88 160h56v24a8 8 0 0 0 16 0v-24h16a8 8 0 0 0 8-8");
}

</style>
