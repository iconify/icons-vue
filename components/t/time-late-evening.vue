<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf6ykxbpu.css';
import '../../css/u/uwpt270ve.css';
import '../../css/g/gk94y4b-q.css';
import '../../css/i/i687abc5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGVD1XseCd" viewBox="0 0 203 203"><path class="kf6ykxbpu"/></symbol><symbol id="SVGeI5oHcAF" viewBox="0 0 197.5 128.5"><path class="uwpt270ve"/></symbol><clipPath id="SVG8jmPYdia"><path class="gk94y4b-q"/></clipPath></defs><g clip-path="url(#SVG8jmPYdia)"><use width="203" height="203" href="#SVGVD1XseCd" transform="translate(154.5 134.5)"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="-15 96.24 96.24; 9 96.24 96.24; -15 96.24 96.24"/></use></g><path class="i687abc5e"/><use width="197.5" height="128.5" href="#SVGeI5oHcAF" transform="translate(210.31 232.95)"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="-6 0; 6 0; -6 0"/></use>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:time-late-evening" /></template>
