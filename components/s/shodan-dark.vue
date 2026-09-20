<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi2ofinfx.css';
import '../../css/s/sll_zg-uo.css';
import '../../css/f/frpmhlbln.css';
import '../../css/u/uzd0xub_o.css';
import '../../css/c/cj4-q0pbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xi2ofinfx"/><linearGradient id="SVGEwno6d8Z" x1="149.045" x2="262.637" y1="63.893" y2="260.639" gradientUnits="userSpaceOnUse"><stop offset="0" class="sll_zg-uo"/><stop offset="1" class="frpmhlbln"/></linearGradient><path fill="url(#SVGEwno6d8Z)" class="uzd0xub_o"/><linearGradient id="SVGrOk0NQtv" x1="288.325" x2="435.052" y1="258.2" y2="467.748" gradientUnits="userSpaceOnUse"><stop offset="0" class="sll_zg-uo"/><stop offset="1" class="frpmhlbln"/></linearGradient><path fill="url(#SVGrOk0NQtv)" class="cj4-q0pbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shodan-dark" /></template>
