<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iua0p6vky.css';
import '../../css/u/ulzgaspjq.css';
import '../../css/s/stcekdbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="iua0p6vky"/><path clip-rule="evenodd" class="ulzgaspjq"/><path class="stcekdbwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:ungroup-by-ref-type" /></template>
