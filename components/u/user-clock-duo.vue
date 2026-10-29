<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a_0c-vozs.css';
import '../../css/g/gpkr_o8bm.css';
import '../../css/o/oe4c91bbg.css';
import '../../css/v/vmhlk0o_i.css';
import '../../css/l/ljeitrr-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a_0c-vozs"/><path class="gpkr_o8bm wm-s"/><path class="oe4c91bbg wm-s"/><path class="vmhlk0o_i wm-s"/><path class="ljeitrr-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-clock-duo" /></template>
