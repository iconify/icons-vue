<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu-vehb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cu-vehb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:satellite" /></template>
