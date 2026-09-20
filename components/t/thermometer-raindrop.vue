<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4f5e1b5a.css';
import '../../css/h/h01-jxany.css';
import '../../css/e/e7304gbzl.css';
import '../../css/n/n2o0epvqg.css';
import '../../css/k/kg6rfkbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVG7o6ULbmV" viewBox="0 0 175 260.9"><path class="i4f5e1b5a"/></symbol><symbol id="SVGfxACtb4E" viewBox="0 0 72 168"><circle class="h01-jxany"/><path class="e7304gbzl"><animateTransform attributeName="transform" calcMode="spline" dur="1s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; 0 18; 0 0"/></path></symbol><symbol id="SVGyUQRqbXk" viewBox="0 0 118 278"><path class="n2o0epvqg"/></symbol><symbol id="SVG7WuMycTc" viewBox="0 0 118 278"><use width="72" height="168" href="#SVGfxACtb4E" transform="translate(23 87)"/><use width="118" height="278" href="#SVGyUQRqbXk"/></symbol><clipPath id="SVGf4cxJc3D"><path class="kg6rfkbfl"/></clipPath></defs><g clip-path="url(#SVGf4cxJc3D)"><use width="175" height="260.9" href="#SVG7o6ULbmV" transform="translate(168.43 123.18)"/></g><use width="118" height="278" href="#SVG7WuMycTc" transform="translate(275 117)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:thermometer-raindrop" /></template>
