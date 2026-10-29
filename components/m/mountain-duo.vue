<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/omloeub3d.css';
import '../../css/t/tzhzk2bji.css';
import '../../css/z/z2v1f6pmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="omloeub3d"/><path class="tzhzk2bji wm-a"/><path class="z2v1f6pmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mountain-duo" /></template>
