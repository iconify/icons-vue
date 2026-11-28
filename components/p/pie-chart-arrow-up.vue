<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtse6qx-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtse6qx-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pie-chart-arrow-up" /></template>
