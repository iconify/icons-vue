<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iso_je_tj.css';
import '../../css/p/p3y33ibxy.css';
import '../../css/y/y_ybzcyuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iso_je_tj"/><path class="p3y33ibxy"/><path class="y_ybzcyuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tree-deciduous-duotone" /></template>
