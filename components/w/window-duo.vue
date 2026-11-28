<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d__e7ub5t.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/ke7wmubdw.css';
import '../../css/g/gxks5mb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d__e7ub5t secondary"/><g class="dt0cm9dhy primary"><path class="ke7wmubdw"/><path class="gxks5mb4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:window-duo" /></template>
