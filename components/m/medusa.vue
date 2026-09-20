<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g56ey5bfi.css';
import '../../css/q/qu9lg2b_c.css';
import '../../css/u/ux_ddxtiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":277};
const content = `<defs><linearGradient id="SVGzusNleCd" x1="-66.697%" x2="108.63%" y1="81.87%" y2="34.419%"><stop offset="26.563%" class="g56ey5bfi"/><stop offset="100%" class="qu9lg2b_c"/></linearGradient></defs><path fill="url(#SVGzusNleCd)" class="ux_ddxtiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:medusa" /></template>
