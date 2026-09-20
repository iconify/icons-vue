<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwjbwobpj.css';
import '../../css/l/l57hr9diu.css';
import '../../css/v/v-b9irtdp.css';
import '../../css/t/tqydiubom.css';
import '../../css/b/bfahyzhwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><clipPath id="SVGbnSAcdgG"><path class="mwjbwobpj"/></clipPath><symbol id="SVGUUWKNc3I" viewBox="0 0 291 291"><circle class="l57hr9diu"/><path class="v-b9irtdp"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="0 145.5 145.5; 45 145.5 145.5"/></path></symbol></defs><g clip-path="url(#SVGbnSAcdgG)"><use width="291" height="291" href="#SVGUUWKNc3I" transform="translate(110.44 110.63)"/></g><path class="tqydiubom"/><path class="bfahyzhwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:time-late-morning" /></template>
