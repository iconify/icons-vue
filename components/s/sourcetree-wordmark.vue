<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eye2jmcul.css';
import '../../css/u/uvvdcns2p.css';
import '../../css/y/ypamjenez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="eye2jmcul"><path class="uvvdcns2p"/><path class="ypamjenez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sourcetree-wordmark" /></template>
