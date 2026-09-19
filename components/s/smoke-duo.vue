<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oa8uxcckh.css';
import '../../css/v/vy_dwwbew.css';
import '../../css/q/qlkb9wqjy.css';
import '../../css/o/olt2-ybec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="oa8uxcckh"/><path class="vy_dwwbew"/><path class="qlkb9wqjy"/><path class="olt2-ybec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:smoke-duo" /></template>
