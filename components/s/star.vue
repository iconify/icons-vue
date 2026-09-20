<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umm606kxf.css';
import '../../css/u/uh31r0biy.css';
import '../../css/d/d471ab08e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":41,"height":41,"top":-0.5};
const content = `<g class="umm606kxf"><path class="uh31r0biy"/><path class="d471ab08e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-stickies-color:star" /></template>
