<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdnqjebwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle r="0" class="vdnqjebwm"><animate id="SVG0cdVlcnN" fill="freeze" attributeName="r" begin="0;SVGftllRbIv.begin+0.6s" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" values="0;11"/><animate fill="freeze" attributeName="opacity" begin="0;SVGftllRbIv.begin+0.6s" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" values="1;0"/></circle><circle r="0" class="vdnqjebwm"><animate id="SVGftllRbIv" fill="freeze" attributeName="r" begin="SVG0cdVlcnN.begin+0.6s" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" values="0;11"/><animate fill="freeze" attributeName="opacity" begin="SVG0cdVlcnN.begin+0.6s" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" values="1;0"/></circle>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="svg-spinners:pulse-2" /></template>
