<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te7zi9bkg.css';
import '../../css/a/a4l89jl3b.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i4f5e1b5a.css';
import '../../css/d/dnkx-9bkw.css';
import '../../css/n/nei-5jbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVGdPJ1vbNB" x1="310.5" x2="425.5" y1="152.5" y2="351.5" gradientUnits="userSpaceOnUse"><stop offset="0" class="te7zi9bkg"/><stop offset=".5" class="te7zi9bkg"/><stop offset="1" class="a4l89jl3b"/></linearGradient><clipPath id="SVGx2lRIdVh"><path class="ft5dv1b6b"><animate attributeName="d" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" values="M168,252H344V380H168Z; M168,220H376V380H168Z; M168,252H344V380H168Z"/></path></clipPath><symbol id="SVG7o6ULbmV" viewBox="0 0 175 260.9"><path class="i4f5e1b5a"/></symbol></defs><path class="dnkx-9bkw"/><path stroke="url(#SVGdPJ1vbNB)" class="nei-5jbko"/><g clip-path="url(#SVGx2lRIdVh)"><use width="175" height="260.9" href="#SVG7o6ULbmV" transform="translate(168.61 119.2)"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:raindrop-measure" /></template>
