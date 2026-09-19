<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp7upebym.css';
import '../../css/k/k8zwn064d.css';
import '../../css/z/zry2zrb8z.css';
import '../../css/q/q1xj7ub5q.css';
import '../../css/l/lmb380bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="xp7upebym"><path class="k8zwn064d"/><path class="zry2zrb8z"/><path class="q1xj7ub5q"/><path class="lmb380bdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:vs-codium" /></template>
