<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/cxx-j6p5y.css';
import '../../css/q/qc92licjy.css';
import '../../css/o/ov-olib_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cxx-j6p5y"/><circle class="qc92licjy"/><path class="ov-olib_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-question-01" /></template>
