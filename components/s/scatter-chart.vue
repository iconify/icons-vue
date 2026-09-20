<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/le5satbnh.css';
import '../../css/d/d1oyksb4f.css';
import '../../css/a/a981qjxtt.css';
import '../../css/a/alf6uubgl.css';
import '../../css/y/ypc3qib2x.css';
import '../../css/q/qe97cg-lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="le5satbnh"/><circle class="d1oyksb4f"/><circle class="a981qjxtt"/><circle class="alf6uubgl"/><circle class="ypc3qib2x"/><path class="qe97cg-lx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:scatter-chart" /></template>
