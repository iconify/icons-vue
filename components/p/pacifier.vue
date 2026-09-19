<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/mlpd71upt.css';
import '../../css/w/w8qiybccg.css';
import '../../css/s/s-eh6tbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="mlpd71upt"/><path class="w8qiybccg"/><path class="s-eh6tbeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:pacifier" /></template>
