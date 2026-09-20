<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/x/xcv6q1bnv.css';
import '../../css/f/fu1903byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><circle class="xcv6q1bnv"/><path class="fu1903byx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-map-earth-1-planet-earth-globe-world" /></template>
