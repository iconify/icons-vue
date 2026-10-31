<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bthw6-b6e.css';
import '../../css/p/psbrtzbgi.css';
import '../../css/j/jy5v87x1r.css';
import '../../css/t/te7zi9bkg.css';
import '../../css/a/a4l89jl3b.css';
import '../../css/s/sza65ac0h.css';
import '../../css/w/wp1vgjbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVGC7sFVdDQ" x1="-7.2" x2="116.4" y1="36.3" y2="250.4" gradientUnits="userSpaceOnUse"><stop offset="0" class="bthw6-b6e"/><stop offset=".5" class="psbrtzbgi"/><stop offset="1" class="jy5v87x1r"/></linearGradient><linearGradient id="SVGuUa98cHQ" x1="-8.7" x2="117.9" y1="33.7" y2="253" gradientUnits="userSpaceOnUse"><stop offset="0" class="te7zi9bkg"/><stop offset=".5" class="te7zi9bkg"/><stop offset="1" class="a4l89jl3b"/></linearGradient><symbol id="SVGPORV8bes" viewBox="0 0 118 278"><path fill="url(#SVGC7sFVdDQ)" stroke="url(#SVGuUa98cHQ)" class="sza65ac0h"/></symbol><symbol id="SVGuDx8IcJd" viewBox="0 0 99.5 70.9"><path class="wp1vgjbpl"/></symbol></defs><use width="118" height="278" href="#SVGPORV8bes" transform="translate(197 117)"/><use width="99.5" height="70.9" href="#SVGuDx8IcJd" transform="translate(314 250)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:thermometer-glass-fahrenheit-fill" /></template>
