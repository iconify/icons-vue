<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mb_m1r3fi.css';
import '../../css/v/vdylksbhi.css';
import '../../css/j/j9dgfb5fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mb_m1r3fi"/><path class="vdylksbhi"/><path clip-rule="evenodd" class="j9dgfb5fm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-square-bold" /></template>
