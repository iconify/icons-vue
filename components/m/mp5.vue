<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uma3x94ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uma3x94ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mp5" /></template>
