<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bftptrbtp.css';
import '../../css/w/wn6e618bi.css';
import '../../css/i/i0b60i0dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bftptrbtp"/><path class="wn6e618bi"/><path class="i0b60i0dz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pizza" /></template>
