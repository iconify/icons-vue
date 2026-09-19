<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fdqlhjbof.css';
import '../../css/m/mpqzm5b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="fdqlhjbof"/><path class="mpqzm5b1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:toolbox" /></template>
