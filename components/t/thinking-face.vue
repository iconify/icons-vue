<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/my0_g5bac.css';
import '../../css/t/t7cusdu_d.css';
import '../../css/a/acm8xxbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="my0_g5bac"/><path class="t7cusdu_d"/><path class="acm8xxbrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:thinking-face" /></template>
