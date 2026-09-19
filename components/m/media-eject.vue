<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="2.75 11.25 13.25 11.25 8 2.75"/><line x1="13.25" x2="2.75" y1="14.25" y2="14.25"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:media-eject" /></template>
