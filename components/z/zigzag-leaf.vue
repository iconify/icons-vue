<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlelzacjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vlelzacjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:zigzag-leaf" /></template>
