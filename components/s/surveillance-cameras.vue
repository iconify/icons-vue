<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xib2qv12u.css';
import '../../css/r/r_69r9b3c.css';
import '../../css/h/hbfbrwbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="xib2qv12u"/><path class="r_69r9b3c"/><path class="hbfbrwbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:surveillance-cameras" /></template>
