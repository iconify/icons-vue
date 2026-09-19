<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wjqhddb9g.css';
import '../../css/q/q1b-_nbpa.css';
import '../../css/f/f3b5r9b5b.css';
import '../../css/t/txzxaf12h.css';
import '../../css/k/kp32w4bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="wjqhddb9g"/><path clip-rule="evenodd" class="q1b-_nbpa"/><path class="f3b5r9b5b"/><path clip-rule="evenodd" class="txzxaf12h"/><path clip-rule="evenodd" class="kp32w4bck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:previous-track" /></template>
