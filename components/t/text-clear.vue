<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dm4x1bp9i.css';
import '../../css/y/yy7qddc7s.css';
import '../../css/c/cuunliqrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dm4x1bp9i"/><path class="yy7qddc7s"/><path class="cuunliqrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-clear" /></template>
