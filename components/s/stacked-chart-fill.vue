<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjy60jbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjy60jbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stacked-chart-fill" /></template>
