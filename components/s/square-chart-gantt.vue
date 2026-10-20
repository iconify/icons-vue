<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io0x69bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io0x69bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-chart-gantt" /></template>
