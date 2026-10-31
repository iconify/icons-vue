<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuk73z6nh.css';
import '../../css/w/wp1vgjbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGAOeApdFp" viewBox="0 0 118 278"><path class="nuk73z6nh"/></symbol><symbol id="SVGuDx8IcJd" viewBox="0 0 99.5 70.9"><path class="wp1vgjbpl"/></symbol></defs><use width="118" height="278" href="#SVGAOeApdFp" transform="translate(197 117)"/><use width="99.5" height="70.9" href="#SVGuDx8IcJd" transform="translate(314 250)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:thermometer-glass-fahrenheit" /></template>
