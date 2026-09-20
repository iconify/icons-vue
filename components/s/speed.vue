<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/i3w0-bidx.css';
import '../../css/b/bjw6ntbil.css';
import '../../css/t/toz5ulbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i3w0-bidx"/><path class="bjw6ntbil"/><path class="toz5ulbud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:speed" /></template>
