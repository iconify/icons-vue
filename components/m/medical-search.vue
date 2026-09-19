<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/ghjhw3b6v.css';
import '../../css/o/opopepb0m.css';
import '../../css/l/ljh670flx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ghjhw3b6v"/><path clip-rule="evenodd" class="opopepb0m"/><path clip-rule="evenodd" class="ljh670flx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:medical-search" /></template>
