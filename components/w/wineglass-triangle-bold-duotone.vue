<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/le29hpbjw.css';
import '../../css/d/dxr69bcwt.css';
import '../../css/v/vck_s2eyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="le29hpbjw"/><path class="dxr69bcwt"/><path class="vck_s2eyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wineglass-triangle-bold-duotone" /></template>
