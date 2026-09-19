<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mj6aybcne.css';
import '../../css/f/fkw3fxcnc.css';
import '../../css/f/ftri9ubwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="mj6aybcne"/><path class="fkw3fxcnc"/><path class="ftri9ubwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-in-manual-wheelchair-facing-right" /></template>
