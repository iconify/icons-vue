<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/vtmphkbxs.css';
import '../../css/y/ypen9ccxg.css';
import '../../css/q/q7ftzha2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vtmphkbxs"/><path class="ypen9ccxg"/><path class="q7ftzha2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:t-shirt" /></template>
