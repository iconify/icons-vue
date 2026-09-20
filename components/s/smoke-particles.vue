<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6smy3bhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGm1nJYdFP" viewBox="0 0 173 217"><circle r="24" opacity="0" class="s6smy3bhi"><animateTransform id="SVGSIWwabXC" additive="sum" attributeName="transform" begin="0s; x1.end+.75s" dur="2.25s" type="translate" values="0 0; -58 -118"/><animate id="SVGwMop6jTM" attributeName="r" begin="0s; y1.end+.75s" dur="2.25s" values="24; 36"/><animate id="SVGpf3xoe5L" attributeName="opacity" begin="0s; y1.end+.75s" dur="2.25s" keyTimes="0; .17; .83; 1" values="0; 1; 1; 0"/></circle><circle r="24" opacity="0" class="s6smy3bhi"><animateTransform id="SVG9UUncbie" additive="sum" attributeName="transform" begin=".83s; x2.end+.75s" dur="2.25s" type="translate" values="0 0; 58 -118"/><animate id="SVGy1y3kexh" attributeName="r" begin=".83s; y2.end+.75s" dur="2.25s" values="24; 36"/><animate id="SVGlVPGvdSQ" attributeName="opacity" begin=".83s; z2.end+.75s" dur="2.25s" keyTimes="0; .17; .83; 1" values="0; 1; 1; 0"/></circle><circle r="24" opacity="0" class="s6smy3bhi"><animateTransform id="SVG6DGESzgM" additive="sum" attributeName="transform" begin="1.66s; x3.end+.75s" dur="2.25s" type="translate" values="0 0; 0 -118"/><animate id="SVGAYOvydkN" attributeName="r" begin="1.66s; y3.end+.75s" dur="2.25s" values="24; 36"/><animate id="SVGsnO4ybfH" attributeName="opacity" begin="1.66s; z3.end+.75s" dur="2.25s" keyTimes="0; .17; .83; 1" values="0; 1; 1; 0"/></circle></symbol></defs><use width="173" height="217" href="#SVGm1nJYdFP" transform="translate(169.5 147.5)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:smoke-particles" /></template>
