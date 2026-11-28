<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_edzg9_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_edzg9_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pie-chart-arrow-up" /></template>
