<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/ztm1hib0j.css';
import '../../css/k/kf0xosbke.css';
import '../../css/x/xgq81cbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path class="ztm1hib0j"/><path class="kf0xosbke"/><path clip-rule="evenodd" class="xgq81cbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:terminal-secure-compact" /></template>
