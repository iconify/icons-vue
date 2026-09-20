<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4owt0n0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4owt0n0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:square-chart-gantt-solid" /></template>
