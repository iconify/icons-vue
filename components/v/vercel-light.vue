<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf68w40sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pf68w40sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vercel-light" /></template>
