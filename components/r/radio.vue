<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hd_q1qbrk.css';
import '../../css/h/h9rbmc90b.css';
import '../../css/g/gms57lb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hd_q1qbrk"/><path class="h9rbmc90b"/><path clip-rule="evenodd" class="gms57lb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:radio" /></template>
