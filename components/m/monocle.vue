<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/o_u0y8bmx.css';
import '../../css/d/de9gu_b1y.css';
import '../../css/f/fw5zavb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="o_u0y8bmx"/><circle class="de9gu_b1y"/><path class="fw5zavb2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:monocle" /></template>
