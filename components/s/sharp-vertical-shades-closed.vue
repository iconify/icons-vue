<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alurfvbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-vertical-shades-closed" /></template>
<style>
.alurfvbwq {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zM13 5h1.5v14H13zm-2 14H9.5V5H11zM6 5h1.5v14H6zm10.5 14V5H18v14z");
}

</style>
