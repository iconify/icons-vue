<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hxu_bbcsk.css';
import '../../css/g/g4o-ggzfa.css';
import '../../css/w/w2-buabqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hxu_bbcsk"/><path class="g4o-ggzfa"/><path class="w2-buabqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:umbrella-bold" /></template>
