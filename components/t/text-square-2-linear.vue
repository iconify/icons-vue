<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d6f12_byi.css';
import '../../css/l/lhx-r4bhy.css';
import '../../css/f/fbyc4_bzy.css';
import '../../css/e/erf8l4xce.css';
import '../../css/h/hf617yxtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d6f12_byi"/><path class="lhx-r4bhy"/><path class="fbyc4_bzy"/><path class="erf8l4xce"/><path class="hf617yxtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-square-2-linear" /></template>
