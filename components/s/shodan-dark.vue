<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi2ofinfx.css';
import '../../css/s/sll_zg-uo.css';
import '../../css/f/frpmhlbln.css';
import '../../css/u/uzd0xub_o.css';
import '../../css/c/cj4-q0pbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xi2ofinfx"/><linearGradient id="SVGAPTIucbS" x1="149" x2="262.6" y1="63.9" y2="260.6" gradientUnits="userSpaceOnUse"><stop offset="0" class="sll_zg-uo"/><stop offset="1" class="frpmhlbln"/></linearGradient><path fill="url(#SVGAPTIucbS)" class="uzd0xub_o"/><linearGradient id="SVG6gp76J3X" x1="288.3" x2="435.1" y1="258.2" y2="467.7" gradientUnits="userSpaceOnUse"><stop offset="0" class="sll_zg-uo"/><stop offset="1" class="frpmhlbln"/></linearGradient><path fill="url(#SVG6gp76J3X)" class="cj4-q0pbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shodan-dark" /></template>
