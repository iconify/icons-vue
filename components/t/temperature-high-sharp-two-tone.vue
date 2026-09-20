<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/d/dw9a-gbpb.css';
import '../../css/n/nw2wqtb4e.css';
import '../../css/u/u8_q54bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dw9a-gbpb"/><path class="nw2wqtb4e"/><path class="u8_q54bsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:temperature-high-sharp-two-tone" /></template>
