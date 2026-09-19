<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/l/l2iib5bto.css';
import '../../css/s/sq_622bov.css';
import '../../css/r/rp1r7sbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="l2iib5bto"/><path class="sq_622bov"/><path class="rp1r7sbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sperm" /></template>
