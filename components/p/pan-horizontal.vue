<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy9yyucwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zy9yyucwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pan-horizontal" /></template>
