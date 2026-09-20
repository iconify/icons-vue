<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bg-drv1xu.css';
import '../../css/u/um-e79spk.css';
import '../../css/p/pxv3brbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bg-drv1xu"/><path clip-rule="evenodd" class="um-e79spk"/><path class="pxv3brbsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:slider-h2" /></template>
