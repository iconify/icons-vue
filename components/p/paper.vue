<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7iewpkkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y7iewpkkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paper" /></template>
