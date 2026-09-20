<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kv8gt_bsu.css';
import '../../css/g/grgvu4bsu.css';
import '../../css/y/yy83lwb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kv8gt_bsu"/><path clip-rule="evenodd" class="grgvu4bsu"/><path class="yy83lwb2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-slider-filled" /></template>
