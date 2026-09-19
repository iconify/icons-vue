<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/u/umfll9bys.css';
import '../../css/c/ceqznzypa.css';
import '../../css/h/h77qjobjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="umfll9bys"/><circle class="ceqznzypa"/><path class="h77qjobjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:transform" /></template>
