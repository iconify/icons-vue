<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/z/z_4m6ybwr.css';
import '../../css/k/k8tcf1rtp.css';
import '../../css/o/o2aiptqim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<radialGradient id="SVG07MMfKot" cx="109.343" cy="539.821" r="6.73" gradientTransform="matrix(0 -64.2714 43.3138 0 -23063.79 7483.99)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="z_4m6ybwr"/></radialGradient><path fill="url(#SVG07MMfKot)" class="k8tcf1rtp"/><radialGradient id="SVGji48leYT" cx="109.359" cy="534.613" r="6.73" gradientTransform="matrix(0 64.2714 -43.3138 0 23350.25 -6972.22)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="z_4m6ybwr"/></radialGradient><path fill="url(#SVGji48leYT)" class="o2aiptqim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sync-in-light" /></template>
