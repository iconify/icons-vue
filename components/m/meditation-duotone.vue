<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iyvy9kbny.css';
import '../../css/h/hwlo84b7e.css';
import '../../css/e/em2u9acce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iyvy9kbny"/><path clip-rule="evenodd" class="hwlo84b7e"/><path class="em2u9acce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:meditation-duotone" /></template>
