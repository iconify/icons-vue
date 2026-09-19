<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/sqp_44b0p.css';
import '../../css/y/y7zppqbne.css';
import '../../css/s/srj0fzbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sqp_44b0p"/><path class="y7zppqbne"/><path class="srj0fzbwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-square" /></template>
