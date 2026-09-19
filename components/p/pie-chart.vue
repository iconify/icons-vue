<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no1dsegho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="no1dsegho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:pie-chart" /></template>
