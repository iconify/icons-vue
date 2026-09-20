<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_90lkbzg.css';
import '../../css/z/zejl7cbiu.css';
import '../../css/f/fzbeawbaw.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/t/t98w45bko.css';
import '../../css/z/zhuiqmm1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="l_90lkbzg"/><path class="zejl7cbiu"/><path class="fzbeawbaw"/><g class="jn8qy4bru"><path class="t98w45bko"/><path class="zhuiqmm1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ram" /></template>
