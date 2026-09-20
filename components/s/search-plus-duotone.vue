<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wf82r5bjl.css';
import '../../css/t/t516tib5y.css';
import '../../css/g/gflmrzp2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wf82r5bjl"/><path clip-rule="evenodd" class="t516tib5y"/><path class="gflmrzp2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-plus-duotone" /></template>
