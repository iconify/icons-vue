<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kfzcnbb6p.css';
import '../../css/r/rm94l1jha.css';
import '../../css/k/k2e-prbdi.css';
import '../../css/q/qd4ogl5wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kfzcnbb6p"/><rect transform="matrix(-1 0 0 -1 24 24)" class="rm94l1jha"/><circle class="k2e-prbdi"/><circle class="qd4ogl5wu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:window-chart-line" /></template>
