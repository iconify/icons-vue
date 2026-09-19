<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/re6v0rlwg.css';
import '../../css/x/x9je47b1o.css';
import '../../css/x/xa9ln-blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="re6v0rlwg"/><path clip-rule="evenodd" class="x9je47b1o"/><path class="xa9ln-blb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:risk-analysis-outline" /></template>
