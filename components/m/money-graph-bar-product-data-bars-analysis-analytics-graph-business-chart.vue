<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po7q84-3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="po7q84-3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:money-graph-bar-product-data-bars-analysis-analytics-graph-business-chart" /></template>
