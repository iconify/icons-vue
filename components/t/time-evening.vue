<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwjbwobpj.css';
import '../../css/v/vmv5bpbix.css';
import '../../css/h/hwi_1ccly.css';
import '../../css/t/tqydiubom.css';
import '../../css/v/v_959zbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><clipPath id="SVGbnSAcdgG"><path class="mwjbwobpj"/></clipPath><symbol id="SVGZIAs5cWk" viewBox="0 0 291.6 290.6"><ellipse class="vmv5bpbix"/><path class="hwi_1ccly"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="0 145.78 145.78; 45 145.78 145.78"/></path></symbol></defs><g clip-path="url(#SVGbnSAcdgG)"><use width="291.6" height="290.6" href="#SVGZIAs5cWk" transform="translate(110.28 168.62)"/></g><path class="tqydiubom"/><path class="v_959zbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:time-evening" /></template>
