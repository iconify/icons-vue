<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/w439gnkso.css';
import '../../css/a/afxiy6lsc.css';
import '../../css/f/fmtboebos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="w439gnkso wm-a"/><path class="afxiy6lsc"/><path class="fmtboebos wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shower-head" /></template>
