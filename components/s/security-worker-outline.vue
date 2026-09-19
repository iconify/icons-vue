<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w_ke1bbey.css';
import '../../css/l/lyv_st-0c.css';
import '../../css/j/j53y1ybih.css';
import '../../css/u/ubczyjues.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="w_ke1bbey"/><path clip-rule="evenodd" class="lyv_st-0c"/><path class="j53y1ybih"/><path clip-rule="evenodd" class="ubczyjues"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:security-worker-outline" /></template>
