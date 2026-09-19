<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njfbj4esg.css';
import '../../css/d/dpptcnn_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njfbj4esg"/><path class="dpptcnn_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:stopwatch" /></template>
