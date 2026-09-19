<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xbgdc1brd.css';
import '../../css/g/gikl4ubov.css';
import '../../css/z/zj5357btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xbgdc1brd"/><path class="gikl4ubov"/><path class="zj5357btx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:rv-duo" /></template>
