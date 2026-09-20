<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i_hswibar.css';
import '../../css/c/ci61avbfu.css';
import '../../css/s/sbhzribxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="ft5dv1b6b"><rect fill="url(#SVGvdp9QbRA)" paint-order="stroke" class="i_hswibar"/><defs><radialGradient id="SVGvdp9QbRA" cx="50%" cy="50%" r="100%" fx="50%" fy="0%" gradientUnits="objectBoundingBox"><stop class="ci61avbfu"/><stop offset="1"/></radialGradient></defs><path class="sbhzribxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:svgl" /></template>
