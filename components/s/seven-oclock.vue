<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2x11_bxr.css';
import '../../css/k/kso7adcaj.css';
import '../../css/e/es25eccir.css';
import '../../css/i/ij2x_72vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGo3sIfGZN" class="p2x11_bxr"/></defs><g class="kso7adcaj"><circle class="es25eccir"/><use href="#SVGo3sIfGZN"/></g><g class="ij2x_72vy"><circle class="es25eccir"/><use href="#SVGo3sIfGZN"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:seven-oclock" /></template>
