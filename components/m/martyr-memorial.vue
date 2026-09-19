<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wty5_-bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wty5_-bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:martyr-memorial" /></template>
