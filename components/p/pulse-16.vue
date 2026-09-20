<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i70r71bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i70r71bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pulse-16" /></template>
