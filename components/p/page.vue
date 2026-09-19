<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0a9vkbzg.css';
import '../../css/r/r8cyu3bwz.css';
import '../../css/m/ms0ewhbdp.css';
import '../../css/e/evh35gd0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="a0a9vkbzg"><rect class="r8cyu3bwz"/><path class="ms0ewhbdp"/><path class="evh35gd0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:page" /></template>
