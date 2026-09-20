<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/s/s8izyxzyl.css';
import '../../css/y/ycbr2ubsi.css';
import '../../css/o/oqga-sb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s8izyxzyl"/><path class="ycbr2ubsi"/><path clip-rule="evenodd" class="oqga-sb1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:piggy-bank-sharp-duotone" /></template>
