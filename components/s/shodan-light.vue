<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k83_4x1-c.css';
import '../../css/d/d-llkv2cb.css';
import '../../css/i/itrz8idgc.css';
import '../../css/u/uzd0xub_o.css';
import '../../css/c/cj4-q0pbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k83_4x1-c"/><linearGradient id="SVGYn2Y3GFM" x1="149" x2="262.6" y1="63.9" y2="260.6" gradientUnits="userSpaceOnUse"><stop offset="0" class="d-llkv2cb"/><stop offset="1" class="itrz8idgc"/></linearGradient><path fill="url(#SVGYn2Y3GFM)" class="uzd0xub_o"/><linearGradient id="SVG0q8vfduD" x1="288.3" x2="435.1" y1="258.2" y2="467.7" gradientUnits="userSpaceOnUse"><stop offset="0" class="d-llkv2cb"/><stop offset="1" class="itrz8idgc"/></linearGradient><path fill="url(#SVG0q8vfduD)" class="cj4-q0pbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shodan-light" /></template>
