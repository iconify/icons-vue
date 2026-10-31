<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te7zi9bkg.css';
import '../../css/a/a4l89jl3b.css';
import '../../css/n/njni8ub9c.css';
import '../../css/l/lrug4j06j.css';
import '../../css/w/wj4__cbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVG99g7Cb5F" x1="220" x2="292" y1="137.7" y2="262.4" gradientUnits="userSpaceOnUse"><stop offset="0" class="te7zi9bkg"/><stop offset=".5" class="te7zi9bkg"/><stop offset="1" class="a4l89jl3b"/></linearGradient><linearGradient id="SVGmfhjSdOC" y1="193.7" y2="318.4" href="#SVG99g7Cb5F"/><linearGradient id="SVGzClBIbJf" y1="249.7" y2="374.4" href="#SVG99g7Cb5F"/></defs><path stroke="url(#SVG99g7Cb5F)" class="njni8ub9c"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="-48 0; 48 0; -48 0"/></path><path stroke="url(#SVGmfhjSdOC)" class="lrug4j06j"><animateTransform additive="sum" attributeName="transform" begin="-1.5s" dur="6s" repeatCount="indefinite" type="translate" values="-48 0; 48 0; -48 0"/></path><path stroke="url(#SVGzClBIbJf)" class="wj4__cbnk"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="48 0; -48 0; 48 0"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:mist-fill" /></template>
