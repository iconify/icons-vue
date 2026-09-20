<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrxpgubkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":272.7,"height":238.5};
const content = `<path class="nrxpgubkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mcdonalds" /></template>
