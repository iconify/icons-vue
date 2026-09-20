<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/skyb51bdr.css';
import '../../css/y/yf2sdkboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="skyb51bdr"/><path class="yf2sdkboz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:navigation-arrow-north" /></template>
