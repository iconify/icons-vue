<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukba4dbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ukba4dbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:pie-chart" /></template>
