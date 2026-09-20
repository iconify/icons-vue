<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlj0scbpf.css';
import '../../css/d/d-2gb0bhq.css';
import '../../css/z/zfjgl05hi.css';
import '../../css/f/fms0nebmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGYqAb8ZRw" viewBox="0 0 375 375"><circle class="vlj0scbpf"/><path class="d-2gb0bhq"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="0 187.5 187.5; 45 187.5 187.5"/></path></symbol><symbol id="SVG62m3Bbns" viewBox="0 0 279 279"><path class="zfjgl05hi"/></symbol><clipPath id="SVG3Rs9aebu"><path class="fms0nebmr"/></clipPath></defs><g clip-path="url(#SVG3Rs9aebu)"><use width="375" height="375" href="#SVGYqAb8ZRw" transform="translate(74.5 76.5)"/></g><use width="279" height="279" href="#SVG62m3Bbns" transform="translate(116.5 116.5)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:solar-eclipse" /></template>
