<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1d3tpb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j1d3tpb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sword-tie" /></template>
