<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf_qlo-zp.css';
import '../../css/v/v5ljivbwn.css';
import '../../css/e/e-vijbbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVGPqbGhekF" x1="187.9" x2="324.1" y1="138.1" y2="373.9" gradientUnits="userSpaceOnUse"><stop offset="0" class="vf_qlo-zp"/><stop offset=".5" class="vf_qlo-zp"/><stop offset="1" class="v5ljivbwn"/></linearGradient></defs><path fill="url(#SVGPqbGhekF)" class="e-vijbbnd"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="rotate" values="-15 256 256; 15 256 256; -15 256 256"/><animate attributeName="opacity" dur="6s" values="1; .75; 1; .75; 1; .75; 1"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:star-fill" /></template>
