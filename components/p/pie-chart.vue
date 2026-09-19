<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opdpygblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opdpygblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pie-chart" /></template>
