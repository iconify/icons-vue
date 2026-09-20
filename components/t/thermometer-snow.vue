<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01-jxany.css';
import '../../css/e/e7304gbzl.css';
import '../../css/n/n2o0epvqg.css';
import '../../css/i/i2kjsom5t.css';
import '../../css/w/w-zwgn2dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGfxACtb4E" viewBox="0 0 72 168"><circle class="h01-jxany"/><path class="e7304gbzl"><animateTransform attributeName="transform" calcMode="spline" dur="1s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; 0 18; 0 0"/></path></symbol><symbol id="SVGyUQRqbXk" viewBox="0 0 118 278"><path class="n2o0epvqg"/></symbol><symbol id="SVG7WuMycTc" viewBox="0 0 118 278"><use width="72" height="168" href="#SVGfxACtb4E" transform="translate(23 87)"/><use width="118" height="278" href="#SVGyUQRqbXk"/></symbol><clipPath id="SVGhmqlMeld"><path class="i2kjsom5t"/></clipPath></defs><g clip-path="url(#SVGhmqlMeld)"><path class="w-zwgn2dr"><animateTransform attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1; .42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="scale" values="1 1; .9 .9; 1 1; .9 .9; 1 1"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1; .42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; 31.4 20.6; 0 0; 31.4 20.6; 0 0"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="rotate" values="-6 314 206; 6 314 206; -6 314 206"/></path></g><use width="118" height="278" href="#SVG7WuMycTc" transform="translate(197 117)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:thermometer-snow" /></template>
