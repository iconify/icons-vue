<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m4ucz2uaw.css';
import '../../css/o/ocio42bgr.css';
import '../../css/t/t584fyapz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="m4ucz2uaw"/><path class="ocio42bgr"/><path class="t584fyapz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:trash5" /></template>
