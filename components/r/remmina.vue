<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fffy1xlok.css';
import '../../css/h/h13cb1w3n.css';
import '../../css/i/iycln-b8i.css';
import '../../css/h/hbt4h80zk.css';
import '../../css/j/ju5f3lb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGKJlEQK7q" x1="365.7" x2="146.3" y1="512" gradientUnits="userSpaceOnUse"><stop offset="0" class="fffy1xlok"/><stop offset="1" class="h13cb1w3n"/></linearGradient><circle fill="url(#SVGKJlEQK7q)" class="iycln-b8i"/><path class="hbt4h80zk"/><path class="ju5f3lb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:remmina" /></template>
