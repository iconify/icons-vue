<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mt96jhb4p.css';
import '../../css/y/yw4fz_b6b.css';
import '../../css/y/yd398tbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mt96jhb4p"/><path class="yw4fz_b6b"/><path class="yd398tbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-circle-duo" /></template>
