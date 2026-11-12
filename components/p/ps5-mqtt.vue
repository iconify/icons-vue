<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjxoumaot.css';
import '../../css/j/j0dgimlyo.css';
import '../../css/i/iycln-b8i.css';
import '../../css/d/d207gzzih.css';
import '../../css/z/zwx4r_96p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGWyKcCcBL" x1="384" x2="128" y1="477.7" y2="34.3" gradientUnits="userSpaceOnUse"><stop offset="0" class="sjxoumaot"/><stop offset="1" class="j0dgimlyo"/></linearGradient><circle fill="url(#SVGWyKcCcBL)" class="iycln-b8i"/><path class="d207gzzih"/><path class="zwx4r_96p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ps5-mqtt" /></template>
