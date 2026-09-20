<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scix5ob1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scix5ob1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:square-chart-gantt" /></template>
