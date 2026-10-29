<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/drfrgy0_d.css';
import '../../css/l/lw875-p4x.css';
import '../../css/p/ps9k3gbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="drfrgy0_d"/><path class="lw875-p4x"/><path class="ps9k3gbsc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:upload-duo" /></template>
