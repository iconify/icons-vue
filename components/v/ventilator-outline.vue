<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l2es_7bef.css';
import '../../css/u/u74184bbs.css';
import '../../css/j/j2f-64b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="l2es_7bef"/><path clip-rule="evenodd" class="u74184bbs"/><path class="j2f-64b_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ventilator-outline" /></template>
