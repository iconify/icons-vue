<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hch4c9obq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hch4c9obq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skeleton" /></template>
