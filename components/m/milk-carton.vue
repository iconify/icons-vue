<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylxpa8bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ylxpa8bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:milk-carton" /></template>
