<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/r/rlix6ub3a.css';
import '../../css/b/bteimacwg.css';
import '../../css/u/u6x4exbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><circle class="rlix6ub3a"/><circle class="bteimacwg"/><path class="u6x4exbvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:voicemail-stroke-16" /></template>
