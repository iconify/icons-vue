<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u709lrbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u709lrbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:star-2-flat" /></template>
