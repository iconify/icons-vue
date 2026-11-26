<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/n/nqf5313bg.css';
import '../../css/i/iukm4cgym.css';
import '../../css/d/d1j8upbii.css';
import '../../css/h/hldbrlh-d.css';
import '../../css/w/w2tnaoa4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><radialGradient id="SVGlvi9Bbxm" cx=".35" cy=".3" r=".8"><stop offset="0" class="vc--wpv5i"/><stop offset=".25" class="nqf5313bg"/><stop offset=".8" class="iukm4cgym"/><stop offset="1" class="d1j8upbii"/></radialGradient></defs><g transform="matrix(4.2 0 0 4.2 256 275.2)"><path fill="url(#SVGlvi9Bbxm)" class="hldbrlh-d"/><ellipse transform="rotate(-35 -27 -33)" class="w2tnaoa4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:red-heart" /></template>
