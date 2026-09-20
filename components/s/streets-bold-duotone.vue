<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fcaaw--es.css';
import '../../css/k/km6q1bmez.css';
import '../../css/u/ut5j5mboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fcaaw--es"/><path class="km6q1bmez"/><path class="ut5j5mboq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-bold-duotone" /></template>
