<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vrga8r-gz.css';
import '../../css/f/fqxr8w82g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vrga8r-gz"/><path clip-rule="evenodd" class="fqxr8w82g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sticker-smile-circle-2-bold" /></template>
