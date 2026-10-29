<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ah371nbbv.css';
import '../../css/v/vfx376v4r.css';
import '../../css/x/xm6k-ibev.css';
import '../../css/t/ti7s0kwlh.css';
import '../../css/r/rcb7clbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ah371nbbv"/><path class="vfx376v4r wm-a"/><path class="wm-a xm6k-ibev"/><path class="ti7s0kwlh"/><path class="rcb7clbki wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:video-call-duo" /></template>
