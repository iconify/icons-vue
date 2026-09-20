<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx95euwke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yx95euwke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:pie-chart-solid" /></template>
