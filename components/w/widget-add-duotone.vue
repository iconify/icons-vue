<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mt6ba2bga.css';
import '../../css/t/t-5vfcbmo.css';
import '../../css/i/ihsle8fcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mt6ba2bga"/><path class="t-5vfcbmo"/><path class="ihsle8fcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:widget-add-duotone" /></template>
