<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aguilgmnz.css';
import '../../css/q/qc4ukd41w.css';
import '../../css/y/ytth9f11g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aguilgmnz wm-k"/><path class="qc4ukd41w wm-shine"/><path class="wm-shine ytth9f11g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:receipt" /></template>
