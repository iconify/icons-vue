<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p14n8bc8l.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k8joftj-v.css';
import '../../css/v/vffpfaczr.css';
import '../../css/n/nzuptnbav.css';
import '../../css/p/pxm2isbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p14n8bc8l secondary"/><g class="dt0cm9dhy primary"><path class="k8joftj-v"/><path class="vffpfaczr"/><path class="nzuptnbav"/><path class="pxm2isbes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tape-measure-duo" /></template>
