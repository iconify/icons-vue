<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulra56alq.css';
import '../../css/a/aw14a30if.css';
import '../../css/y/yr_1obcsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ulra56alq"><path class="aw14a30if"/><path class="yr_1obcsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:robots" /></template>
