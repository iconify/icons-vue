<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls6_xn_4i.css';
import '../../css/m/m26d08bnp.css';
import '../../css/s/sxmz7tbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ls6_xn_4i"><path class="m26d08bnp"/><path class="sxmz7tbxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:text" /></template>
