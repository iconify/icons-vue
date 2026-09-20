<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4pxhybqf.css';
import '../../css/k/k8_kgmb2o.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/i/icah0vbzx.css';
import '../../css/c/cujl162ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="o4pxhybqf"/><path class="k8_kgmb2o"/><g class="jn8qy4bru"><path class="icah0vbzx"/><path class="cujl162ys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:puzzle-piece" /></template>
