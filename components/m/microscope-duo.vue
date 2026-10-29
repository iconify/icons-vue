<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l5-ny61uz.css';
import '../../css/k/kgfx3e43q.css';
import '../../css/p/p8yrg0x8f.css';
import '../../css/y/yt69a67rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l5-ny61uz wm-a"/><path class="kgfx3e43q wm-a"/><path class="p8yrg0x8f"/><path class="wm-a yt69a67rh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:microscope-duo" /></template>
