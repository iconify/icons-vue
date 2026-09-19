<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvmupi87j.css';
import '../../css/w/wx-066bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gvmupi87j"/><path class="wx-066bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:transform-language" /></template>
