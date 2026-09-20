<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7rvl6bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v7rvl6bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-ai-flow" /></template>
