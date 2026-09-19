<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qzqh5nesu.css';
import '../../css/m/m6daittia.css';
import '../../css/n/n0h4l1b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="qzqh5nesu"/><path class="m6daittia"/><path clip-rule="evenodd" class="n0h4l1b9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rdt-result-no-test" /></template>
