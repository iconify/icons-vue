<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k83_4x1-c.css';
import '../../css/d/d-llkv2cb.css';
import '../../css/i/itrz8idgc.css';
import '../../css/u/uzd0xub_o.css';
import '../../css/c/cj4-q0pbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k83_4x1-c"/><linearGradient id="SVGgvJg9bTS" x1="149.045" x2="262.637" y1="63.893" y2="260.639" gradientUnits="userSpaceOnUse"><stop offset="0" class="d-llkv2cb"/><stop offset="1" class="itrz8idgc"/></linearGradient><path fill="url(#SVGgvJg9bTS)" class="uzd0xub_o"/><linearGradient id="SVGEP5I9bhs" x1="288.325" x2="435.052" y1="258.2" y2="467.748" gradientUnits="userSpaceOnUse"><stop offset="0" class="d-llkv2cb"/><stop offset="1" class="itrz8idgc"/></linearGradient><path fill="url(#SVGEP5I9bhs)" class="cj4-q0pbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shodan-light" /></template>
