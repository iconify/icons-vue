<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x4pbug86i.css';
import '../../css/l/l7fiaob4l.css';
import '../../css/w/w4xi5ecbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="x4pbug86i"/><path class="l7fiaob4l"/><path clip-rule="evenodd" class="w4xi5ecbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:wash-hands-outline" /></template>
