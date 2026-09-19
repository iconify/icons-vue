<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/y/y_ggmwbci.css';
import '../../css/l/l3b_1nbnj.css';
import '../../css/r/r2une0btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y_ggmwbci"/><path class="l3b_1nbnj"/><path class="r2une0btx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:map-pin-check" /></template>
