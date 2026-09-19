<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mpaozksdi.css';
import '../../css/w/wdiqrzjxb.css';
import '../../css/e/erq7bzoxe.css';
import '../../css/k/k-w74vgau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="mpaozksdi"/><path class="wdiqrzjxb"/><path class="erq7bzoxe"/><path class="k-w74vgau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:reduce-decimal-places" /></template>
