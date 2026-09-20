<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1aoolbul.css';
import '../../css/t/tb9i-5hiz.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/m/muk_sco2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b1aoolbul"/><linearGradient id="SVGOrt0keYM" x1="197.808" x2="313.942" y1="197.22" y2="314.528" gradientUnits="userSpaceOnUse"><stop offset="0" class="tb9i-5hiz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGOrt0keYM)" class="muk_sco2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pve-notebuddy-light" /></template>
