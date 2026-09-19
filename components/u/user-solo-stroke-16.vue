<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/t/tc3hrxbmr.css';
import '../../css/x/xho4_r_6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><circle class="tc3hrxbmr"/><path class="xho4_r_6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-solo-stroke-16" /></template>
