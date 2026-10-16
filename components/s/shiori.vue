<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y83-mxdaj.css';
import '../../css/m/mdqiz-ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":117.173,"height":117.173};
const content = `<g transform="translate(-39.688 -207.42)"><circle class="y83-mxdaj"/><path class="mdqiz-ben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:shiori" /></template>
