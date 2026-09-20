<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e2ra9zmqo.css';
import '../../css/r/rbrqs4bqf.css';
import '../../css/f/fedou6bod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e2ra9zmqo"/><path class="rbrqs4bqf"/><path class="fedou6bod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:routing-3-bold" /></template>
