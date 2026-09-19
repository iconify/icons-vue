<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2ym7bcla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y2ym7bcla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skateboarding-01" /></template>
