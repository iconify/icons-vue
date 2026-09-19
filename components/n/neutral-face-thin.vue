<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/r/r1zv4vbmm.css';
import '../../css/r/rsjsrjd2a.css';
import '../../css/l/lwa-rvbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="r1zv4vbmm"/><path class="rsjsrjd2a"/><path class="lwa-rvbps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:neutral-face-thin" /></template>
