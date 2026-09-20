<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb2r0lzlb.css';
import '../../css/w/wnkunhbrw.css';
import '../../css/w/w6-vq0bkj.css';
import '../../css/x/x7mpwpjvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVGnpneLCAV" x1="38.8" x2="133.4" y1="20.8" y2="184.6" gradientUnits="userSpaceOnUse"><stop offset="0" class="cb2r0lzlb"/><stop offset=".5" class="cb2r0lzlb"/><stop offset="1" class="wnkunhbrw"/></linearGradient><symbol id="SVGj2o8pd2H" viewBox="0 0 192.5 192.5"><path fill="url(#SVGnpneLCAV)" class="w6-vq0bkj"/></symbol></defs><path class="x7mpwpjvl"/><use width="192.5" height="192.5" href="#SVGj2o8pd2H" transform="translate(159.76 139.76)"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="-15 96.24 96.24; 9 96.24 96.24; -15 96.24 96.24"/></use>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:time-late-night-fill" /></template>
