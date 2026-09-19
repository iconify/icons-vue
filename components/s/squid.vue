<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad4jeu_wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ad4jeu_wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:squid" /></template>
