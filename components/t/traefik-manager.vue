<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7_8e2b0j.css';
import '../../css/i/icj9dmb5t.css';
import '../../css/i/ibogbvhlc.css';
import '../../css/i/i4ks7abcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGGEFIQe0B" x1="-47.4" x2="559.4" y1="-47.4" y2="559.4" gradientUnits="userSpaceOnUse"><stop offset="0" class="x7_8e2b0j"/><stop offset=".5" class="x7_8e2b0j"/><stop offset=".75" class="icj9dmb5t"/><stop offset="1" class="ibogbvhlc"/></linearGradient><path fill="url(#SVGGEFIQe0B)" class="i4ks7abcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:traefik-manager" /></template>
