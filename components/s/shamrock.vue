<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-x7ggbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-x7ggbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shamrock" /></template>
