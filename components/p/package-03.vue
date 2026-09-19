<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/g/g5uq_vbhz.css';
import '../../css/z/ztkbymavw.css';
import '../../css/e/e5s_c9bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g5uq_vbhz"/><path class="ztkbymavw"/><path class="e5s_c9bsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-03" /></template>
