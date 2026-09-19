<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hbu191xru.css';
import '../../css/d/de_jnj1nk.css';
import '../../css/x/xlvsdp5ws.css';
import '../../css/q/q2en493ek.css';
import '../../css/e/eembw2ujo.css';
import '../../css/v/v2aim8bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><circle class="hbu191xru"/><path class="de_jnj1nk"/><path class="xlvsdp5ws"/><path class="q2en493ek"/><path class="eembw2ujo"/><path class="v2aim8bmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:refresh-print" /></template>
