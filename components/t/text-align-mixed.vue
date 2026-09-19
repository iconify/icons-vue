<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/judw4ebii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="judw4ebii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-align-mixed" /></template>
