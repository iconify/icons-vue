<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e6fsq3dmz.css';
import '../../css/e/es5c5ho5q.css';
import '../../css/y/yivdtj5uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e6fsq3dmz"/><path class="es5c5ho5q"/><path class="yivdtj5uu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-minimalistic-broken" /></template>
