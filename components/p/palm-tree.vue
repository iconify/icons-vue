<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mm2szcbmu.css';
import '../../css/x/x8-a5_dkh.css';
import '../../css/q/qcfnobbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mm2szcbmu"/><path class="x8-a5_dkh"/><path class="qcfnobbty wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:palm-tree" /></template>
