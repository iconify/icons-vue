<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f9kfjgbxq.css';
import '../../css/q/q1y4cdbvh.css';
import '../../css/w/wd6v8jb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f9kfjgbxq"/><path class="q1y4cdbvh"/><path class="wd6v8jb0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:phone-call-filled" /></template>
