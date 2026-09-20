<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/mf3bfro8i.css';
import '../../css/j/j-46ttn1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mf3bfro8i"/><circle transform="matrix(-1 0 0 1 12 12)" class="j-46ttn1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:minus-five-circle-line" /></template>
