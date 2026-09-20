<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9qsbpbzw.css';
import '../../css/w/wdf-683ve.css';
import '../../css/k/kviuzd8ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGCGm8Bb2z" viewBox="0 0 178 178"><path class="z9qsbpbzw"/></symbol><symbol id="SVGLlWB2cAN" viewBox="0 0 359 231"><path class="wdf-683ve"/></symbol><symbol id="SVGItYSIeIf" viewBox="0 0 435.5 371.5"><g clip-path="url(#SVGab30RcjT)"><use width="178" height="178" href="#SVGCGm8Bb2z" transform="translate(77 118)"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="-15 86 86; 9 86 86; -15 86 86"/></use></g><use width="359" height="231" href="#SVGLlWB2cAN" transform="translate(76.5 140.5)"/></symbol><clipPath id="SVGab30RcjT"><path class="kviuzd8ma"/></clipPath></defs><use width="435.5" height="371.5" href="#SVGItYSIeIf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:partly-cloudy-night" /></template>
