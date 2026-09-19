<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/f/fo9q7n9ez.css';
import '../../css/o/ocruyxbsi.css';
import '../../css/q/qoybt6q_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="fo9q7n9ez"/><path class="ocruyxbsi"/><rect class="qoybt6q_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:spoon" /></template>
