<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuumn07mq.css';
import '../../css/l/lzm1bzrhh.css';
import '../../css/l/l0xanab5d.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/h/hxivuvthh.css';
import '../../css/s/s920ixbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fuumn07mq"/><path class="lzm1bzrhh"/><path class="l0xanab5d"/><g class="ij2x_72vy"><path class="hxivuvthh"/><path class="s920ixbuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:umbrella" /></template>
