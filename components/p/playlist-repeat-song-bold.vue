<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4kr7db0h.css';
import '../../css/g/g-vmp1bpt.css';
import '../../css/t/tdirdccsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="k4kr7db0h"><path class="g-vmp1bpt"/><path class="tdirdccsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:playlist-repeat-song-bold" /></template>
