<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh569x-ti.css';
import '../../css/i/i9d56db8d.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/k/kebej8zjv.css';
import '../../css/s/sdm1hnz8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="sh569x-ti"/><path class="i9d56db8d"/><g class="ij2x_72vy"><path class="kebej8zjv"/><path class="sdm1hnz8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:roasted-sweet-potato" /></template>
