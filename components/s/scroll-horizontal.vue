<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o0gr6kbmk.css';
import '../../css/l/lsot8vkjb.css';
import '../../css/k/kvmdo0b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o0gr6kbmk"/><path class="lsot8vkjb"/><path class="kvmdo0b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:scroll-horizontal" /></template>
