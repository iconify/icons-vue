<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtuk_yb9d.css';
import '../../css/h/h01-jxany.css';
import '../../css/e/e7304gbzl.css';
import '../../css/n/n2o0epvqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVG5U0yObnr" viewBox="0 0 99.5 70.9"><path class="mtuk_yb9d"/></symbol><symbol id="SVGH13itTBE" viewBox="0 0 72 168"><circle class="h01-jxany"/><path class="e7304gbzl"><animateTransform attributeName="transform" calcMode="spline" dur="1s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; 0 18; 0 0"/></path></symbol><symbol id="SVG1F6KxcIf" viewBox="0 0 118 278"><path class="n2o0epvqg"/></symbol><symbol id="SVGGfxIadkq" viewBox="0 0 118 278"><use width="72" height="168" href="#SVGH13itTBE" transform="translate(23 87)"/><use width="118" height="278" href="#SVG1F6KxcIf"/></symbol></defs><use width="99.5" height="70.9" href="#SVG5U0yObnr" transform="translate(314 250)"/><use width="118" height="278" href="#SVGGfxIadkq" transform="translate(197 117)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:thermometer-fahrenheit" /></template>
