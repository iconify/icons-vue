<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy81sn_wu.css';
import '../../css/f/fmwemwbtd.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/f/fw8ogsv2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGP3Ht5bwy" x1="177.6" x2="50.8" y1="266.2" y2="304.5" gradientUnits="userSpaceOnUse"><stop offset="0" class="uy81sn_wu"/><stop offset=".596" class="fmwemwbtd"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGP3Ht5bwy)" class="fw8ogsv2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:webtrees" /></template>
