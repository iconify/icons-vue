<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbk_ibhxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbk_ibhxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pie-chart-search" /></template>
