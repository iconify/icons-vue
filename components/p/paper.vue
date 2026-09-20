<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/y/y2yhntbjs.css';
import '../../css/e/ezi0_rbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="h01tyzbfu"><path class="y2yhntbjs"/><circle class="ezi0_rbbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:paper" /></template>
