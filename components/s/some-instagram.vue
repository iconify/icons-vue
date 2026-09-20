<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mz8vdhbwm.css';
import '../../css/t/t09fqbbpt.css';
import '../../css/j/jjmucv4qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mz8vdhbwm"/><path class="t09fqbbpt"/><path clip-rule="evenodd" class="jjmucv4qj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:some-instagram" /></template>
