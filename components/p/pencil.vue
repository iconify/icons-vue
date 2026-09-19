<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="1.75 11.25 1.75 14.25 4.75 14.25 14.25 4.75 11.25 1.75"/><line x1="8.75" x2="11.25" y1="4.75" y2="7.25"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:pencil" /></template>
