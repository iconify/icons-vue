<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh6i7hbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oh6i7hbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:x-axis" /></template>
