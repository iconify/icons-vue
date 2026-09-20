<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1enzdbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1enzdbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:presentation-chart-line" /></template>
