<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfbsps-lm.css';
import '../../css/d/dj56hf47g.css';
import '../../css/c/ci2nsc7wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGksseleyt" x1="125.101" x2="386.996" y1="429.111" y2="167.217" gradientUnits="userSpaceOnUse"><stop offset="0" class="hfbsps-lm"/><stop offset="1" class="dj56hf47g"/></linearGradient><path fill="url(#SVGksseleyt)" class="ci2nsc7wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mysterium-node" /></template>
