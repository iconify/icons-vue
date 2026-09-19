<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivo15gtnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ivo15gtnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:report-growth" /></template>
