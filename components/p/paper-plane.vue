<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="1.75 1.75 14.25 7.75 1.75 14.25 3.25 7.75"/><line x1="3.75" x2="7.25" y1="7.75" y2="7.75"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:paper-plane" /></template>
