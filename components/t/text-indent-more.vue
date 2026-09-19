<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tui3x3bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tui3x3bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-indent-more" /></template>
