<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hdzj-zbni.css';
import '../../css/x/xm4-qxbrj.css';
import '../../css/k/kfu7dr89j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hdzj-zbni"/><path clip-rule="evenodd" class="xm4-qxbrj"/><path class="kfu7dr89j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:posts-carousel-vertical-outline" /></template>
