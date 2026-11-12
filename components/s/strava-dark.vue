<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1w56ebrl.css';
import '../../css/c/c0xyygbvy.css';
import '../../css/u/u1e8aucpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGNwww7djp" x1="-25" x2="537" y1="93.7" y2="418.3" gradientUnits="userSpaceOnUse"><stop offset="0" class="v1w56ebrl"/><stop offset="1" class="c0xyygbvy"/></linearGradient><path fill="url(#SVGNwww7djp)" class="u1e8aucpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:strava-dark" /></template>
