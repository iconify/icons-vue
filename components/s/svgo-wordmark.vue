<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnr0c4bhl.css';
import '../../css/p/p3pc--btm.css';
import '../../css/k/kqiz83f1h.css';
import '../../css/p/pb3hujugu.css';
import '../../css/l/l5uv_ibbi.css';
import '../../css/j/j93_zbbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGzQ8HKeQI" x1="263.36" x2="333.47" y1="14.74" y2="84.85" gradientUnits="userSpaceOnUse"><stop offset="0" class="bnr0c4bhl"/><stop offset="1" class="p3pc--btm"/></linearGradient><linearGradient id="SVGhjumLdWT" x1="262.64" x2="332.75" y1="15.46" y2="85.57" gradientTransform="translate(0 45.625)scale(.3672)" href="#SVGzQ8HKeQI"/><linearGradient id="SVGVLisPh9F" x1="263.36" x2="333.47" y1="14.74" y2="84.85" gradientTransform="translate(0 45.625)scale(.3672)" gradientUnits="userSpaceOnUse" href="#SVGzQ8HKeQI"/></defs><path class="kqiz83f1h text"/><path fill="url(#SVGVLisPh9F)" class="pb3hujugu"/><path fill="url(#SVGhjumLdWT)" class="l5uv_ibbi"/><path class="j93_zbbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:svgo-wordmark" /></template>
