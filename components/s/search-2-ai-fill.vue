<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8tcwf7xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8tcwf7xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:search-2-ai-fill" /></template>
