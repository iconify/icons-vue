<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9dt5acfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i9dt5acfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stone-block" /></template>
