<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="9.25 13.25 2.75 13.25 2.75 2.75 13.25 2.75 13.25 9.25"/><polyline points="8.75 13.25 8.75 8.75 13.25 8.75"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:sticky-note" /></template>
