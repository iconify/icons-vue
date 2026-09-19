<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8_yuipxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e8_yuipxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xlm" /></template>
