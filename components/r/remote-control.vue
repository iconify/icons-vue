<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fjk_47b8s.css';
import '../../css/z/zq1i1eb4q.css';
import '../../css/h/h2u2p5b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fjk_47b8s"/><path class="wm-a zq1i1eb4q"/><path class="h2u2p5b7j wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:remote-control" /></template>
