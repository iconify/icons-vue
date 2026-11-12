<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4b-kdb-c.css';
import '../../css/f/f-c80ro0i.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/c/ct___5r2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s4b-kdb-c"/><linearGradient id="SVGB9jXnevF" x1="33" x2="327" y1="64.3" y2="418.2" gradientUnits="userSpaceOnUse"><stop offset="0" class="f-c80ro0i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGB9jXnevF)" class="ct___5r2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:steam-deck-light" /></template>
