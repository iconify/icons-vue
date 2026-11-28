<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xogt69b4f.css';
import '../../css/z/zonae0b0d.css';
import '../../css/b/bae79bbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xogt69b4f"/><path class="zonae0b0d"/><path class="bae79bbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:move-vertical" /></template>
