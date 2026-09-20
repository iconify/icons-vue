<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujo1e-bph.css';
import '../../css/l/lflolvmwv.css';
import '../../css/i/iycln-b8i.css';
import '../../css/t/t3esu9bda.css';
import '../../css/c/c75b9o_ub.css';
import '../../css/p/p-udrf0du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGGOYJkbWS" x1="256" x2="256" y1="790" y2="278" gradientTransform="translate(0 -278)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ujo1e-bph"/><stop offset="1" class="lflolvmwv"/></linearGradient><circle fill="url(#SVGGOYJkbWS)" class="iycln-b8i"/><path class="t3esu9bda"/><path class="c75b9o_ub"/><path class="p-udrf0du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:telegram" /></template>
