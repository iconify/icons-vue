<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ut8cuhtwq.css';
import '../../css/k/kbs4yj5cx.css';
import '../../css/n/nzciehbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ut8cuhtwq"/><path class="kbs4yj5cx"/><path class="nzciehbug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wallet3-filled" /></template>
