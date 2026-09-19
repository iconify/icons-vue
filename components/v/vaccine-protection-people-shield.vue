<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/jtybx7bnc.css';
import '../../css/m/mtc995bac.css';
import '../../css/c/cjriokfje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jtybx7bnc"/><path class="mtc995bac"/><path class="cjriokfje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:vaccine-protection-people-shield" /></template>
