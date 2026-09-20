<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qrjnaipku.css';
import '../../css/k/kknkqexjp.css';
import '../../css/m/mex7ymchk.css';
import '../../css/x/xr5b5tbwe.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="qrjnaipku"/><path class="kknkqexjp"/><path class="mex7ymchk"/><path class="xr5b5tbwe"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:text-bubbles-off" /></template>
