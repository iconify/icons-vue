<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h12mmx6jh.css';
import '../../css/u/u4l8uj5fs.css';
import '../../css/h/hg6hx7b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="h12mmx6jh"/><path class="u4l8uj5fs"/><path class="hg6hx7b4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:power-print" /></template>
