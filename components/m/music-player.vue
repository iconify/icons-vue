<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ub0p2rb4l.css';
import '../../css/n/nd_emezuh.css';
import '../../css/q/qznqlw_ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ub0p2rb4l"/><path class="nd_emezuh"/><path class="qznqlw_ir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:music-player" /></template>
