<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/ymtnnmbxm.css';
import '../../css/f/fs6qilbac.css';
import '../../css/z/z4vu3bcgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ymtnnmbxm"/><path class="fs6qilbac"/><path class="z4vu3bcgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:spleen-outline-24px" /></template>
