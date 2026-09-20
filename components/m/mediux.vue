<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5cbf9bul.css';
import '../../css/y/y6fki-bri.css';
import '../../css/f/f3lmxkbrs.css';
import '../../css/q/q9z5dbb7d.css';
import '../../css/b/btn2cqbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGUdgXmbcx" x1="256" x2="256" y1="2" y2="514" gradientTransform="matrix(1 0 0 -1 0 514)" gradientUnits="userSpaceOnUse"><stop offset="0" class="q5cbf9bul"/><stop offset=".237" class="y6fki-bri"/><stop offset="1" class="f3lmxkbrs"/></linearGradient><path fill="url(#SVGUdgXmbcx)" class="q9z5dbb7d"/><path class="btn2cqbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mediux" /></template>
