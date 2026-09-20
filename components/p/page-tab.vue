<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hlgjvjvel.css';
import '../../css/l/l45iarbss.css';
import '../../css/u/uw9kubtnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hlgjvjvel"/><path class="l45iarbss"/><path class="uw9kubtnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:page-tab" /></template>
