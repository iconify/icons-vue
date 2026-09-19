<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbxsf3bxy.css';
import '../../css/l/lczsmyy_j.css';
import '../../css/m/m7u4wybxw.css';
import '../../css/i/ife7p1z_o.css';
import '../../css/i/igoz3eb9s.css';
import '../../css/n/nysrv6iwu.css';
import '../../css/g/gtm7goick.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGDO9yw0hz" x1="0" x2="1" y1="0" y2="0" gradientTransform="matrix(0 43.04975 -45.37783 0 19.508 .808)" gradientUnits="userSpaceOnUse"><stop offset="0" class="rbxsf3bxy"/><stop offset=".614" class="rbxsf3bxy"/><stop offset="1" class="lczsmyy_j"/></linearGradient><linearGradient id="SVG3F0mwbRC" x1="0" x2="1" y1="0" y2="0" gradientTransform="matrix(0 38.07518 -40.13424 0 31.263 3.346)" gradientUnits="userSpaceOnUse"><stop offset="0" class="m7u4wybxw"/><stop offset=".7" class="ife7p1z_o"/></linearGradient></defs><path fill="url(#SVGDO9yw0hz)" transform="translate(0 42)" class="igoz3eb9s"/><path fill="url(#SVG3F0mwbRC)" transform="translate(0 42)" class="nysrv6iwu"/><path class="gtm7goick"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:opera-wordmark" /></template>
