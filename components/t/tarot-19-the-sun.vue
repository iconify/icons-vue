<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0sgzib0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p0sgzib0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-19-the-sun" /></template>
