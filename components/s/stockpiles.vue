<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew93jbbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ew93jbbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stockpiles" /></template>
