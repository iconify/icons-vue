<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/d/d098hyf_v.css';
import '../../css/x/xeb-fib6w.css';
import '../../css/c/ciu-kx8bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d098hyf_v"/><path class="xeb-fib6w"/><path class="ciu-kx8bj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podium-3-sharp-fill" /></template>
