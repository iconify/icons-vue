<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/y/yh2a82bhg.css';
import '../../css/d/dm44abbrd.css';
import '../../css/q/qgoe78bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yh2a82bhg"/><path class="dm44abbrd"/><path class="qgoe78bty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ranking2" /></template>
