<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/r/ryp3spl8y.css';
import '../../css/g/gu2s0cb7j.css';
import '../../css/c/czbbm17fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ryp3spl8y"/><path class="gu2s0cb7j"/><path class="czbbm17fv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-cart-sharp-duotone" /></template>
