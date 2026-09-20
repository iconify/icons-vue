<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb9s8pbmn.css';
import '../../css/x/x1ldb7bmu.css';
import '../../css/f/fesr6pspg.css';
import '../../css/l/lngldfetz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGFVZY5dGN" x1="201.5" x2="1225.5" y1="177.505" y2="-846.495" gradientTransform="matrix(.4 0 0 -.4 -29.4 122.2)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cb9s8pbmn"/><stop offset="1" class="x1ldb7bmu"/></linearGradient><path fill="url(#SVGFVZY5dGN)" class="fesr6pspg"/><path class="lngldfetz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-registrations" /></template>
