<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te7zi9bkg.css';
import '../../css/a/a4l89jl3b.css';
import '../../css/x/x5epiqw7g.css';
import '../../css/n/nsk5251jp.css';
import '../../css/q/qoa-8ibxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVGj6U3ceGK" x1="138.5" x2="224.2" y1="5.1" y2="153.5" gradientUnits="userSpaceOnUse"><stop offset="0" class="te7zi9bkg"/><stop offset=".5" class="te7zi9bkg"/><stop offset="1" class="a4l89jl3b"/></linearGradient><linearGradient id="SVGeAVxmbDm" x1="77.7" x2="169" y1="96.2" y2="254.4" href="#SVGj6U3ceGK"/><symbol id="SVG91MKyccO" viewBox="0 0 348 240"><path stroke="url(#SVGj6U3ceGK)" class="x5epiqw7g"><animate attributeName="stroke-dashoffset" dur="6s" repeatCount="indefinite" values="0; 2960"/></path><path stroke="url(#SVGeAVxmbDm)" class="nsk5251jp"><animate attributeName="stroke-dashoffset" dur="6s" repeatCount="indefinite" values="0; 1540"/></path></symbol></defs><use width="348" height="240" href="#SVG91MKyccO" transform="translate(82 136)"/><path class="qoa-8ibxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:wind-beaufort-6-fill" /></template>
