<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pxu_y3blz.css';
import '../../css/q/qkn6ysiyx.css';
import '../../css/h/ha5gndbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pxu_y3blz"/><path class="qkn6ysiyx"/><path clip-rule="evenodd" class="ha5gndbef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:young-people-outline" /></template>
