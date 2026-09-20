<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvd31abxp.css';
import '../../css/c/cdofe-b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nvd31abxp"/><path class="cdofe-b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:spline-area-chart" /></template>
