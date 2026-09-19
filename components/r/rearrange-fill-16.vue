<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xz6d5opni.css';
import '../../css/t/trnmlvb1m.css';
import '../../css/s/sq7kakbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><rect class="xz6d5opni"/><rect class="trnmlvb1m"/><rect class="sq7kakbys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:rearrange-fill-16" /></template>
