<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvfd0ac0r.css';
import '../../css/u/uih-2ib5h.css';
import '../../css/h/h01-jxany.css';
import '../../css/e/e7304gbzl.css';
import '../../css/n/n2o0epvqg.css';
import '../../css/i/i2kjsom5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVG7LDBabQh" viewBox="0 0 193 193"><circle class="fvfd0ac0r"/><path class="uih-2ib5h"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="0 96.5 96.5; 45 96.5 96.5"/></path></symbol><symbol id="SVGfxACtb4E" viewBox="0 0 72 168"><circle class="h01-jxany"/><path class="e7304gbzl"><animateTransform attributeName="transform" calcMode="spline" dur="1s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; 0 18; 0 0"/></path></symbol><symbol id="SVGyUQRqbXk" viewBox="0 0 118 278"><path class="n2o0epvqg"/></symbol><symbol id="SVG7WuMycTc" viewBox="0 0 118 278"><use width="72" height="168" href="#SVGfxACtb4E" transform="translate(23 87)"/><use width="118" height="278" href="#SVGyUQRqbXk"/></symbol><clipPath id="SVGhmqlMeld"><path class="i2kjsom5t"/></clipPath></defs><g clip-path="url(#SVGhmqlMeld)"><use width="193" height="193" href="#SVG7LDBabQh" transform="translate(217.5 109.5)"/></g><use width="118" height="278" href="#SVG7WuMycTc" transform="translate(197 117)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:thermometer-sun" /></template>
