<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs6j3rbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="vs6j3rbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:money-graph-bar-decrease-arrow-product-performance-down-decrease-graph-business-chart" /></template>
