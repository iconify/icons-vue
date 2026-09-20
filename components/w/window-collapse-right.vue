<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/f/f6r4u0dcm.css';
import '../../css/p/pd1h9oded.css';
import '../../css/e/eo6qbob6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="f6r4u0dcm"/><path class="pd1h9oded"/><path class="eo6qbob6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:window-collapse-right" /></template>
