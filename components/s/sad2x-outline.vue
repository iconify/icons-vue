<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wb5ffvplm.css';
import '../../css/u/u99lp1b_s.css';
import '../../css/s/siob3cbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="wb5ffvplm"/><path clip-rule="evenodd" class="u99lp1b_s"/><path clip-rule="evenodd" class="siob3cbvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sad2x-outline" /></template>
