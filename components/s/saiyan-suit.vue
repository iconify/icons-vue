<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bggtgrogs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bggtgrogs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:saiyan-suit" /></template>
