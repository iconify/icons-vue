<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtjkxs4jc.css';
import '../../css/o/ouc1l9qwb.css';
import '../../css/l/l8x8yogyg.css';
import '../../css/q/qt6hcj3lh.css';
import '../../css/d/dcgdlwb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wtjkxs4jc"/><path class="ouc1l9qwb"/><path class="l8x8yogyg"/><path class="qt6hcj3lh"/><path class="dcgdlwb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:scroll" /></template>
