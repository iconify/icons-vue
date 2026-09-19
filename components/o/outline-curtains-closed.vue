<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhsacpclm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-curtains-closed" /></template>
<style>
.vhsacpclm {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zM13 5v14h-2V5zM6 5h3v14H6zm9 14V5h3v14z");
}

</style>
