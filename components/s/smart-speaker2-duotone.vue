<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g1pyxgm9j.css';
import '../../css/u/uq0_eabch.css';
import '../../css/y/yz4p29iab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g1pyxgm9j"/><path class="uq0_eabch"/><path class="yz4p29iab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:smart-speaker2-duotone" /></template>
