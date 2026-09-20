<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/m3h3otklp.css';
import '../../css/t/t10y6eb2y.css';
import '../../css/j/jo7dc815i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="m3h3otklp"/><path class="t10y6eb2y"/><path class="jo7dc815i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rotation" /></template>
