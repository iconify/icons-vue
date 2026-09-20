<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf6ykxbpu.css';
import '../../css/x/x7mpwpjvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGVD1XseCd" viewBox="0 0 203 203"><path class="kf6ykxbpu"/></symbol></defs><path class="x7mpwpjvl"/><use width="203" height="203" href="#SVGVD1XseCd" transform="translate(154.5 134.5)"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="-15 96.24 96.24; 9 96.24 96.24; -15 96.24 96.24"/></use>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:time-late-night" /></template>
