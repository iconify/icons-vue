<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eq_3nt3js.css';
import '../../css/r/r0ch1sbxc.css';
import '../../css/j/j798wsbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eq_3nt3js"/><path clip-rule="evenodd" class="r0ch1sbxc"/><path class="j798wsbhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:money-plus" /></template>
