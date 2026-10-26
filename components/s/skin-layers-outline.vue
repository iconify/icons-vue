<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h_p0abc2u.css';
import '../../css/e/e0cq7z_ut.css';
import '../../css/o/oigydacdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="h_p0abc2u"/><path clip-rule="evenodd" class="e0cq7z_ut"/><path class="oigydacdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:skin-layers-outline" /></template>
