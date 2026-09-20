<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te7zi9bkg.css';
import '../../css/a/a4l89jl3b.css';
import '../../css/n/njni8ub9c.css';
import '../../css/l/lrug4j06j.css';
import '../../css/w/wj4__cbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVGffxWZc2j" x1="220" x2="292" y1="137.7" y2="262.4" gradientUnits="userSpaceOnUse"><stop offset="0" class="te7zi9bkg"/><stop offset=".5" class="te7zi9bkg"/><stop offset="1" class="a4l89jl3b"/></linearGradient><linearGradient id="SVGzdZdTcoE" y1="193.7" y2="318.4" href="#SVGffxWZc2j"/><linearGradient id="SVGNpocRctX" y1="249.7" y2="374.4" href="#SVGffxWZc2j"/></defs><path stroke="url(#SVGffxWZc2j)" class="njni8ub9c"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="-48 0; 48 0; -48 0"/></path><path stroke="url(#SVGzdZdTcoE)" class="lrug4j06j"><animateTransform additive="sum" attributeName="transform" begin="-1.5s" dur="6s" repeatCount="indefinite" type="translate" values="-48 0; 48 0; -48 0"/></path><path stroke="url(#SVGNpocRctX)" class="wj4__cbnk"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="48 0; -48 0; 48 0"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:mist-fill" /></template>
