<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vobd55u4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="play-outline"><path class="(Stroke) 54 Vector vobd55u4d" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:play-outline" /></template>
