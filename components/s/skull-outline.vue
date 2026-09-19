<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v90n_sbfk.css';
import '../../css/r/rs9a2ybyz.css';
import '../../css/g/gnokhxweg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="v90n_sbfk"/><path class="rs9a2ybyz"/><path clip-rule="evenodd" class="gnokhxweg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:skull-outline" /></template>
