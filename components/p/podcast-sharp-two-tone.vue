<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/is9k_idfr.css';
import '../../css/i/igs6bnbke.css';
import '../../css/k/kil06obbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="is9k_idfr"/><path class="igs6bnbke"/><path class="kil06obbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podcast-sharp-two-tone" /></template>
