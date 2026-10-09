<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsqrtwbgr.css';
import '../../css/y/y3ygpgbwz.css';
import '../../css/e/eia-tm77s.css';
import '../../css/f/fd646mbuc.css';
import '../../css/e/ehc07rbtk.css';
import '../../css/g/g0s742bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jsqrtwbgr"/><path class="y3ygpgbwz"/><path class="eia-tm77s"/><path class="fd646mbuc"/><path class="ehc07rbtk"/><path class="g0s742bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-panel-check-20-bold" /></template>
