<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/x/xtis6_vbr.css';
import '../../css/s/sy99x-beb.css';
import '../../css/y/ymt-x2xna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="xtis6_vbr"/><path class="sy99x-beb"/><path class="ymt-x2xna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:smartphone-cutout-print" /></template>
