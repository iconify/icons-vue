<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi6to1cst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gi6to1cst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-metric" /></template>
