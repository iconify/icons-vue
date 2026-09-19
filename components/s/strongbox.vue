<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mgdslvb_p.css';
import '../../css/q/qv7d25b0i.css';
import '../../css/c/cym6v7rqr.css';
import '../../css/t/t0bcbybdf.css';
import '../../css/j/j589m8jck.css';
import '../../css/m/mjn73rb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="mgdslvb_p"/><path class="qv7d25b0i"/><path class="cym6v7rqr"/><path class="t0bcbybdf"/><path class="j589m8jck"/><path class="mjn73rb1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:strongbox" /></template>
