<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybq5mxb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybq5mxb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:numbers-90-sort-ascending-fill" /></template>
