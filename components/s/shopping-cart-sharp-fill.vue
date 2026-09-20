<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/a/aoal70b6v.css';
import '../../css/y/ycfh6nbib.css';
import '../../css/c/czbbm17fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="aoal70b6v"/><path class="ycfh6nbib"/><path class="czbbm17fv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-cart-sharp-fill" /></template>
