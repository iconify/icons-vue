<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="8.25 3.75 8.25 12.25 14.25 8"/><polygon points="1.75 3.75 1.75 12.25 7.75 8"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:media-fast-forward" /></template>
