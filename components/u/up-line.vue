<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzhq6p0xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzhq6p0xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:up-line" /></template>
