<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/zvxrz6bfm.css';
import '../../css/n/ncgcfebjl.css';
import '../../css/t/tvn32_g5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zvxrz6bfm"/><path class="ncgcfebjl"/><path class="tvn32_g5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-tick" /></template>
