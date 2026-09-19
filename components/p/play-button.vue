<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_7gcnbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t_7gcnbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:play-button" /></template>
