<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm197obpp.css';
import '../../css/i/i4f5e1b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><clipPath id="SVGNZM2LaXo"><path class="cm197obpp"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="scale" values="1 1; 1 .95; 1 1"/></path></clipPath><symbol id="SVG7o6ULbmV" viewBox="0 0 175 260.9"><path class="i4f5e1b5a"/></symbol></defs><use width="175" height="260.9" href="#SVG7o6ULbmV" transform="translate(214.5 123.62)"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="scale" values="1 1; 1 .9; 1 1"/></use><g clip-path="url(#SVGNZM2LaXo)"><use width="175" height="260.9" href="#SVG7o6ULbmV" transform="translate(122.5 123.62)"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="scale" values="1 .9; 1 1; 1 .9"/></use></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:raindrops" /></template>
