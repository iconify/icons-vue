<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_mzln9eu.css';
import '../../css/k/kso7adcaj.css';
import '../../css/e/es25eccir.css';
import '../../css/i/ij2x_72vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGGiJDleTg" class="m_mzln9eu"/></defs><g class="kso7adcaj"><circle class="es25eccir"/><use href="#SVGGiJDleTg"/></g><g class="ij2x_72vy"><circle class="es25eccir"/><use href="#SVGGiJDleTg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:nine-thirty" /></template>
