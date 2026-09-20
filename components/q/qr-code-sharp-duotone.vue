<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/n/nxtylxbax.css';
import '../../css/n/ndwh9bcsg.css';
import '../../css/m/msxn8u5pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nxtylxbax"/><path class="ndwh9bcsg"/><path class="msxn8u5pj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:qr-code-sharp-duotone" /></template>
