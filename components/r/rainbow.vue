<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cimc4ua1c.css';
import '../../css/u/uwpt270ve.css';
import '../../css/b/bom1_ma_h.css';
import '../../css/v/vt9os9bck.css';
import '../../css/r/rcve237pi.css';
import '../../css/o/ok1srg-dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><clipPath id="SVGeNclzYme"><path class="cimc4ua1c"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="-12 0; 12 0; -12 0"/></path></clipPath><symbol id="SVGU9wQYEts" viewBox="0 0 197.5 128.5"><path class="uwpt270ve"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="-12 0; 12 0; -12 0"/></path></symbol></defs><g clip-path="url(#SVGeNclzYme)" class="bom1_ma_h"><path class="vt9os9bck"/><path class="rcve237pi"/><path class="ok1srg-dr"/></g><use width="197.5" height="128.5" href="#SVGU9wQYEts" transform="translate(235.94 219.59)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:rainbow" /></template>
