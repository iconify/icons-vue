<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y1qnj5-tg.css';
import '../../css/j/jo3mazmao.css';
import '../../css/m/mnnnnrphu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y1qnj5-tg"/><path class="jo3mazmao"/><path class="mnnnnrphu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:prison-guard" /></template>
