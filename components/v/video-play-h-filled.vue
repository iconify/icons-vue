<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xupi7pbch.css';
import '../../css/p/pdl1bhbxu.css';
import '../../css/l/l4cuvtbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xupi7pbch"/><path clip-rule="evenodd" class="pdl1bhbxu"/><path class="l4cuvtbmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-play-h-filled" /></template>
