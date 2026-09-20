<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/te1o1iy7a.css';
import '../../css/f/fewy_veac.css';
import '../../css/g/g9ct16bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="te1o1iy7a"/><path clip-rule="evenodd" class="fewy_veac"/><path class="g9ct16bty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sort-alpha-duotone" /></template>
