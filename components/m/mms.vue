<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhtkhwboa.css';
import '../../css/z/z600ygqlh.css';
import '../../css/o/ouq7y6d3w.css';
import '../../css/x/xfsflobmm.css';
import '../../css/f/fls75h9qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qhtkhwboa"/><path class="z600ygqlh"/><g class="ouq7y6d3w"><circle class="xfsflobmm"/><path class="fls75h9qh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:mms" /></template>
