<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/k5-6_q3ke.css';
import '../../css/i/ideagcboz.css';
import '../../css/e/e5x2664gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k5-6_q3ke"/><rect class="ideagcboz"/><path class="e5x2664gk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:subtract-square-multiple" /></template>
