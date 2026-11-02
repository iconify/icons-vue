<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjuv2pbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjuv2pbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:translate-line" /></template>
