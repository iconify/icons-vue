<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/x3yd9f_ef.css';
import '../../css/z/z_3uwpbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x3yd9f_ef"/><path class="z_3uwpbtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:playlist-add" /></template>
