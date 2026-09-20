<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iyqk6dbpw.css';
import '../../css/c/c-jivptzw.css';
import '../../css/v/vgvnd_kez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iyqk6dbpw"/><path class="c-jivptzw"/><path class="vgvnd_kez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:posts-carousel-horizontal-bold" /></template>
