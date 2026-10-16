<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl0b0_yrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":83};
const content = `<path class="yl0b0_yrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vert" /></template>
