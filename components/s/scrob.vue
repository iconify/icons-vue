<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0rtl-btu.css';
import '../../css/p/ppx8e3bah.css';
import '../../css/r/r_0yy7e2a.css';
import '../../css/o/o1evwtb9e.css';
import '../../css/a/aq8b6tnwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGEpolebXM" x1="242.906" x2="242.906" y1="514" y2=".881" gradientTransform="matrix(1 0 0 -1 0 514)" gradientUnits="userSpaceOnUse"><stop offset="0" class="v0rtl-btu"/><stop offset=".5" class="ppx8e3bah"/><stop offset="1" class="r_0yy7e2a"/></linearGradient><path fill="url(#SVGEpolebXM)" class="o1evwtb9e"/><linearGradient id="SVGOlJoPoNN" x1="-695.013" x2="-695.013" y1="792.541" y2="793.672" gradientTransform="matrix(96.58 0 0 -96.58 67561.21 76990.172)" gradientUnits="userSpaceOnUse"><stop offset="0" class="v0rtl-btu"/><stop offset="1" class="r_0yy7e2a"/></linearGradient><circle fill="url(#SVGOlJoPoNN)" class="aq8b6tnwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scrob" /></template>
