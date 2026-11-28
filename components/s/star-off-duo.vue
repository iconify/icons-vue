<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7ce9qpex.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t0ut8sbjx.css';
import '../../css/i/iayx1qbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7ce9qpex secondary"/><g class="dt0cm9dhy primary"><path class="t0ut8sbjx"/><path class="iayx1qbsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:star-off-duo" /></template>
