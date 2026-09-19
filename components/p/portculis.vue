<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7f4k2dyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t7f4k2dyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:portculis" /></template>
