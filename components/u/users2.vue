<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/twame7b2s.css';
import '../../css/m/myxf3373x.css';
import '../../css/h/hbvgbz8qr.css';
import '../../css/h/h2t2ttb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="twame7b2s"/><path class="myxf3373x"/><path clip-rule="evenodd" class="hbvgbz8qr"/><path class="h2t2ttb1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:users2" /></template>
