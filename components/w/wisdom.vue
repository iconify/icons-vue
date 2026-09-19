<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuj49nmbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vuj49nmbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wisdom" /></template>
