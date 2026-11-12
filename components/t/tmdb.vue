<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbhh_cjyv.css';
import '../../css/v/vopj28bjv.css';
import '../../css/b/by6ghcj9t.css';
import '../../css/q/qgw5xlb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGZsPISboe" x2="512" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="nbhh_cjyv"/><stop offset=".56" class="vopj28bjv"/><stop offset="1" class="by6ghcj9t"/></linearGradient><path fill="url(#SVGZsPISboe)" class="qgw5xlb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tmdb" /></template>
