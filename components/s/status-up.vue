<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cdyu3tbss.css';
import '../../css/f/fdwcfrbsd.css';
import '../../css/k/kvqd6bcxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cdyu3tbss"/><path class="fdwcfrbsd"/><path class="kvqd6bcxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:status-up" /></template>
