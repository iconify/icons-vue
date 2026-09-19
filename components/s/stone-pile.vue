<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo-n8x3at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jo-n8x3at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stone-pile" /></template>
