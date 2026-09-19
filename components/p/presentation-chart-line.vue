<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ritlmmzok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ritlmmzok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:presentation-chart-line" /></template>
