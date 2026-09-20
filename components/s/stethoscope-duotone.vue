<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/me86ccc_a.css';
import '../../css/f/f4s_wibfo.css';
import '../../css/x/x-yo1fvtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="me86ccc_a"/><path class="f4s_wibfo"/><path class="x-yo1fvtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stethoscope-duotone" /></template>
