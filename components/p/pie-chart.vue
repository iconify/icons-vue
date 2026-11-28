<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vszxc3bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vszxc3bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pie-chart" /></template>
