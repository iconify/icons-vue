<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/s/stui2mbih.css';
import '../../css/l/lybzu4bfv.css';
import '../../css/m/mt26t4l-x.css';
import '../../css/g/go5-q36_y.css';
import '../../css/c/cpue61bhx.css';
import '../../css/s/s3eksd_0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGZad1u4qS" x1="48" x2="48" y1="97.75" y2="2.25" gradientTransform="matrix(1 0 0 -1 0 97.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs><path class="lybzu4bfv"/><path class="mt26t4l-x"/><path class="go5-q36_y"/><path class="cpue61bhx"/><path fill="url(#SVGZad1u4qS)" class="s3eksd_0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:visualstudio" /></template>
