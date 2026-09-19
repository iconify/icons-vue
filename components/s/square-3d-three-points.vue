<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/zj2x5idrr.css';
import '../../css/l/lxen9-max.css';
import '../../css/e/e1pt3ydbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="zj2x5idrr"/><path class="lxen9-max"/><path class="e1pt3ydbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:square-3d-three-points" /></template>
