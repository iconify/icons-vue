<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/se-jdubva.css';
import '../../css/o/or-t-y_mm.css';
import '../../css/q/q-55d_bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="se-jdubva"/><path class="or-t-y_mm wm-a"/><path class="q-55d_bvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ticket-duo" /></template>
