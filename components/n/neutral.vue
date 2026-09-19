<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n87g3vegy.css';
import '../../css/s/sfpa_vabo.css';
import '../../css/j/j76_xebgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="n87g3vegy"/><path class="sfpa_vabo"/><path clip-rule="evenodd" class="j76_xebgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:neutral" /></template>
