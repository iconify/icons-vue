<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykd9cjbnf.css';
import '../../css/f/fqk8mibcy.css';
import '../../css/m/mzvj1ot7y.css';
import '../../css/l/l8meg91xy.css';
import '../../css/m/mhnfz8baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVG3DzpkcMe" x1="115" x2="179.4" y1="91.4" y2="203" gradientUnits="userSpaceOnUse"><stop offset="0" class="ykd9cjbnf"/><stop offset=".5" class="ykd9cjbnf"/><stop offset="1" class="fqk8mibcy"/></linearGradient><symbol id="SVG7N5UAb2o" viewBox="0 0 294.4 294.4"><circle fill="url(#SVG3DzpkcMe)" class="mzvj1ot7y"/><path class="l8meg91xy"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="0 147.2 147.2; 45 147.2 147.2"/></path></symbol></defs><path class="mhnfz8baj"/><use width="294.4" height="294.4" href="#SVG7N5UAb2o" transform="translate(108.68 70.93)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:time-afternoon-fill" /></template>
