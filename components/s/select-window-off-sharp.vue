<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqckgmbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:select-window-off-sharp" /></template>
<style>
.wqckgmbvf {
  fill: currentColor;
  d: path("M20.475 23.3L10.175 13H4v7h12v-4.025l2 2V22H2V9h4v-.175L.675 3.5L2.1 2.075l19.8 19.8zM18 15.125L15.875 13l-4-4H18v4h2V6H8.875L6.15 3.275V2H22v13h-4z");
}

</style>
