<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/k/kbiztcb2v.css';
import '../../css/e/e32cg_bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kbiztcb2v"><animate fill="freeze" attributeName="opacity" dur="0.12s" values="0;1"/><animate fill="freeze" attributeName="stroke-dashoffset" calcMode="spline" dur="0.5s" keySplines="0.65 0 0.35 1" keyTimes="0;1" values="52.06;0"/></path><g opacity=".5"><circle class="e32cg_bao"><animate fill="freeze" attributeName="opacity" dur="0.2s" keyTimes="0;0.4;1" values="0;0;1"/><animate fill="freeze" attributeName="stroke-dashoffset" calcMode="spline" dur="0.58s" keySplines="0 0 1 1;0.65 0 0.35 1" keyTimes="0;0.138;1" values="19.61;19.61;0"/></circle></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:show-draw" /></template>
