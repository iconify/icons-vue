<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj_3qbben.css';
import '../../css/t/tb9i-5hiz.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/m/muk_sco2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tj_3qbben"/><linearGradient id="SVGf7kZMe2C" x1="197.8" x2="313.9" y1="197.2" y2="314.5" gradientUnits="userSpaceOnUse"><stop offset="0" class="tb9i-5hiz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGf7kZMe2C)" class="muk_sco2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pve-notebuddy-light" /></template>
