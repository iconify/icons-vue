<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kknkqexjp.css';
import '../../css/m/mex7ymchk.css';
import '../../css/x/xr5b5tbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="kknkqexjp"/><path class="mex7ymchk"/><path class="xr5b5tbwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:text-bubbles" /></template>
