<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz1pg6brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gz1pg6brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wooden-pegleg" /></template>
