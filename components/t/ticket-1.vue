<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j5a-8dbop.css';
import '../../css/i/i76vj15xh.css';
import '../../css/t/ttse8lbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="j5a-8dbop"/><path class="i76vj15xh"/><path class="ttse8lbkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:ticket-1" /></template>
