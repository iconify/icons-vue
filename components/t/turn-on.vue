<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpvb-o6bq.css';
import '../../css/d/dsi1pmbus.css';
import '../../css/w/waumx2bcm.css';
import '../../css/g/grd4zezfg.css';
import '../../css/w/wgsf-seru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="rpvb-o6bq"><path class="dsi1pmbus"/><path class="waumx2bcm"/><path class="grd4zezfg"/><path class="wgsf-seru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:turn-on" /></template>
