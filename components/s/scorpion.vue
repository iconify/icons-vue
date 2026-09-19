<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsisly3do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fsisly3do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:scorpion" /></template>
