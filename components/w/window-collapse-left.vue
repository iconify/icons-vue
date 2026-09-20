<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/f/f6r4u0dcm.css';
import '../../css/d/dxmmmk1qu.css';
import '../../css/f/fspniabin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="f6r4u0dcm"/><path class="dxmmmk1qu"/><path class="fspniabin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:window-collapse-left" /></template>
