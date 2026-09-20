<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t0bdzibjv.css';
import '../../css/f/fygz0y4og.css';
import '../../css/z/z2ah-61oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t0bdzibjv"/><path class="fygz0y4og"/><path class="z2ah-61oe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shop-broken" /></template>
