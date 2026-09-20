<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuk73z6nh.css';
import '../../css/o/orexe2b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVG7ARWWbSl" viewBox="0 0 118 278"><path class="nuk73z6nh"/></symbol><symbol id="SVGR15heb5B" viewBox="0 0 109.1 73.2"><path class="orexe2b-x"/></symbol></defs><use width="118" height="278" href="#SVG7ARWWbSl" transform="translate(197 117)"/><use width="109.1" height="73.2" href="#SVGR15heb5B" transform="translate(314 250)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:thermometer-glass-celsius" /></template>
