<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/a008irbqj.css';
import '../../css/w/wjmydx_nr.css';
import '../../css/q/qr6637bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="a008irbqj"/><path class="wjmydx_nr"/><path class="qr6637bwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:vegetables" /></template>
