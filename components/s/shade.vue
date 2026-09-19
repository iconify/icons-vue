<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/lbebdjpjw.css';
import '../../css/g/gvnlxzqyt.css';
import '../../css/q/qp833-mnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="lbebdjpjw"/><path class="gvnlxzqyt"/><path class="qp833-mnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:shade" /></template>
