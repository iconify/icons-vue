<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv_rmbk8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zv_rmbk8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:money-graph-bar-increase-up-product-performance-increase-arrow-graph-business-chart" /></template>
