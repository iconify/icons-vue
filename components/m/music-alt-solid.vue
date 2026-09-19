<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/en1u28uhj.css';
import '../../css/v/vg2wr6byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="en1u28uhj"/><path clip-rule="evenodd" class="vg2wr6byn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:music-alt-solid" /></template>
