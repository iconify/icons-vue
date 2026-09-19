<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yrp8owbwe.css';
import '../../css/d/dgp6cjnjf.css';
import '../../css/m/mvz31c87g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yrp8owbwe"/><path class="dgp6cjnjf"/><path class="mvz31c87g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:snow-bold" /></template>
