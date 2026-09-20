<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0n9dqb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0n9dqb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pie-chart-2" /></template>
