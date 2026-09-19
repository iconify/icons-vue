<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jssoprxmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="star-outline"><path class="Vector jssoprxmo" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:star-outline" /></template>
