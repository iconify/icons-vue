<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/f/fsan3yarc.css';
import '../../css/x/xoh-v2bac.css';
import '../../css/d/d3d1cnb2j.css';
import '../../css/r/rgkpd4izd.css';
import '../../css/u/u2i66ifye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><rect class="fsan3yarc"/><path class="xoh-v2bac"/><path class="d3d1cnb2j"/><path class="rgkpd4izd"/><path class="u2i66ifye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:view-grid-detail" /></template>
