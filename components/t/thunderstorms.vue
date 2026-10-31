<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdf-683ve.css';
import '../../css/e/egqkt_b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGywfqvcxz" viewBox="0 0 359 231"><path class="wdf-683ve"/></symbol><symbol id="SVGeZpLBdXU" viewBox="0 0 96 176"><path class="egqkt_b7m"><animate id="SVGfQ2cBnbC" attributeName="opacity" begin="0s;SVGfQ2cBnbC.end+.67s" dur="1.33s" keyTimes="0; .38; .5; .63; .75; .86; .94; 1" values="1; 1; 0; 1; 0; 1; 0; 1"/></path></symbol></defs><use width="359" height="231" href="#SVGywfqvcxz" transform="translate(76.5 140.5)"/><use width="96" height="176" href="#SVGeZpLBdXU" transform="translate(208 293)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:thunderstorms" /></template>
