<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dc_kbr8xr.css';
import '../../css/v/v3bilzbwu.css';
import '../../css/q/qecunebco.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dc_kbr8xr"/><path clip-rule="evenodd" class="v3bilzbwu"/><path clip-rule="evenodd" class="qecunebco"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:raise-hand-off" /></template>
