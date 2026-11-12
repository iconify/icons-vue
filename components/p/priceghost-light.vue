<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kckc1iwlf.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/i/im1e3vbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGaDbyRwJt" x1="211.5" x2="300.5" y1="3.8" y2="508.2" gradientUnits="userSpaceOnUse"><stop offset="0" class="kckc1iwlf"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGaDbyRwJt)" class="im1e3vbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:priceghost-light" /></template>
