<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blg0q0b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="blg0q0b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rattlesnake" /></template>
