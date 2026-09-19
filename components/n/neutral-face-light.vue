<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/az0dxebks.css';
import '../../css/n/nxcr2vf7w.css';
import '../../css/f/frl_qifow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="az0dxebks"/><path class="nxcr2vf7w"/><path class="frl_qifow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:neutral-face-light" /></template>
