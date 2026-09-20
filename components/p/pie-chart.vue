<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t84a0c3hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t84a0c3hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pie-chart" /></template>
