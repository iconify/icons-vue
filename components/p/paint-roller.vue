<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rdqyx1m-i.css';
import '../../css/k/k75sbgkul.css';
import '../../css/h/hrbbo3b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rdqyx1m-i"/><path class="k75sbgkul"/><path class="hrbbo3b9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:paint-roller" /></template>
