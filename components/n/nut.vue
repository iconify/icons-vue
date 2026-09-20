<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/n/nj69sobsr.css';
import '../../css/o/oy8-2ebuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(4 3)" class="jtowsomii"><path class="nj69sobsr"/><circle class="oy8-2ebuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:nut" /></template>
