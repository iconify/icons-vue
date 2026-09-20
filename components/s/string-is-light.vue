<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6qntjvwm.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/w/wigdudbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGf0PPXbFA" x1="256" x2="256" y1="0" y2="364.116" gradientUnits="userSpaceOnUse"><stop offset="0" class="a6qntjvwm"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGf0PPXbFA)" class="wigdudbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:string-is-light" /></template>
