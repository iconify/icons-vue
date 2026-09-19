<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eikm90bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eikm90bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-chart-gantt" /></template>
