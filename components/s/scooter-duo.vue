<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lch3s_b1x.css';
import '../../css/w/wqxztlbrk.css';
import '../../css/z/zjouw2d4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lch3s_b1x"/><path class="wqxztlbrk"/><path class="zjouw2d4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:scooter-duo" /></template>
