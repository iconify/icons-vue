<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d3iab9b0e.css';
import '../../css/z/zx4z7abfl.css';
import '../../css/v/v_r-dov2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d3iab9b0e"/><path class="zx4z7abfl"/><path class="v_r-dov2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:play-stream-linear" /></template>
