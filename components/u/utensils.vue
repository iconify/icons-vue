<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/oztnz4lum.css';
import '../../css/j/j8adolbjh.css';
import '../../css/l/lcbr24bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oztnz4lum"/><path class="j8adolbjh"/><path class="lcbr24bbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:utensils" /></template>
