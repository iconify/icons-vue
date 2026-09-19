<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx0y8b1vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cx0y8b1vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rexx" /></template>
