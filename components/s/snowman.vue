<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzq5e4blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mzq5e4blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:snowman" /></template>
