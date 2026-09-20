<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hni2gnbts.css';
import '../../css/v/vlj0scbpf.css';
import '../../css/d/d-2gb0bhq.css';
import '../../css/w/wio751brs.css';
import '../../css/i/iye24ubqq.css';
import '../../css/q/qogbpyl3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><clipPath id="SVGClf4gb3K"><path class="hni2gnbts"/></clipPath><symbol id="SVGFt3PseFu" viewBox="0 0 375 375"><circle class="vlj0scbpf"/><path class="d-2gb0bhq"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="0 192 192; 45 192 192"/></path></symbol></defs><g clip-path="url(#SVGClf4gb3K)"><use width="375" height="375" href="#SVGFt3PseFu" transform="translate(68.5 68.5)"/><path class="wio751brs"/></g><rect class="iye24ubqq"/><path class="qogbpyl3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:uv-index-5" /></template>
