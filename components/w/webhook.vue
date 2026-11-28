<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nacman8nc.css';
import '../../css/b/b_avhwbzz.css';
import '../../css/n/nho4eobhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nacman8nc"/><path class="b_avhwbzz"/><path class="nho4eobhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:webhook" /></template>
