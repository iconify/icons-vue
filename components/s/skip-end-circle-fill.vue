<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjeuv2d3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qjeuv2d3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-end-circle-fill" /></template>
