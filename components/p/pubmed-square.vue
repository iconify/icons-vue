<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv-52pbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="hv-52pbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:pubmed-square" /></template>
