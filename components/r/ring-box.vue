<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddkx88bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ddkx88bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ring-box" /></template>
