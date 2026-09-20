<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb9i-5hiz.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/t/tfdkf_i9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<radialGradient id="SVGKO1Psbma" cx="260.444" cy="455.503" r="843.338" gradientTransform="matrix(1 0 0 -1 0 514)" gradientUnits="userSpaceOnUse"><stop offset="0" class="tb9i-5hiz"/><stop offset=".34" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGKO1Psbma)" class="tfdkf_i9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nginx-ui-light" /></template>
