<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_ljy4b7o.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/r/r-s7y6bgr.css';
import '../../css/j/jmibpchcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="k_ljy4b7o"/><g class="ij2x_72vy"><path class="r-s7y6bgr"/><path class="jmibpchcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:page-facing-up" /></template>
