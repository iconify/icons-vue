<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipvl157gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ipvl157gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:underhand" /></template>
