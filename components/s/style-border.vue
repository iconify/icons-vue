<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h100pjbuq.css';
import '../../css/e/eeb6_wvec.css';
import '../../css/a/azw0f7azy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h100pjbuq"><path class="eeb6_wvec"/><path class="azw0f7azy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:style-border" /></template>
